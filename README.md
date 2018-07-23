# OpenGL-ES-Programming-Guide
apple hide this document in search result.back up
 Introduction 

 Checklist for Building OpenGL ES Apps for iOS 

 Choosing Which OpenGL ES Versions to Support 

 Verifying OpenGL ES Capabilities 

 Choosing a Rendering Destination 

 Integrating with iOS 

 Implementing a Rendering Engine 

 Debugging and Profiling 

 Configuring OpenGL ES Contexts 

 EAGL Is the iOS Implementation of an OpenGL ES Rendering Context 

 The Current Context Is the Target for OpenGL ES Function Calls 

 Every Context Targets a Specific Version of OpenGL ES 

 An EAGL Sharegroup Manages OpenGL ES Objects for the Context 

 Drawing with OpenGL ES and GLKit 

 A GLKit View Draws OpenGL ES Content on Demand 

 Creating and Configuring a GLKit View 

 Drawing With a GLKit View 

 Rendering Using a Delegate Object 

 A GLKit View Controller Animates OpenGL ES Content 

 Understanding the Animation Loop 

 Using a GLKit View Controller 

 Using GLKit to Develop Your Renderer 

 Handling Vector and Matrix Math 

 Migrating from the OpenGL ES 1.1 Fixed-Function Pipeline 

 Loading Texture Data 

 Drawing to Other Rendering Destinations 

 Creating a Framebuffer Object 

 Creating Offscreen Framebuffer Objects 

 Using Framebuffer Objects to Render to a Texture 

 Rendering to a Core Animation Layer 

 Drawing to a Framebuffer Object 

 Rendering on Demand or with an Animation Loop 

 Rendering a Frame 

 Clear Buffers 

 Prepare Resources and Execute Drawing Commands 

 Execute Drawing Commands 

 Resolve Multisampling 

 Discard Unneeded Renderbuffers 

 Present the Results to Core Animation 

 Using Multisampling to Improve Image Quality 

 Multitasking, High Resolution, and Other iOS Features 

 Implementing a Multitasking-Aware OpenGL ES App 

 Background Apps May Not Execute Commands on the Graphics Hardware 

 Delete Easily Re-Created Resources Before Moving to the Background 

 Supporting High-Resolution Displays 

 Supporting Multiple Interface Orientations 

 Presenting OpenGL ES Content on External Displays 

 OpenGL ES Design Guidelines 

 How to Visualize OpenGL ES 

 OpenGL ES as a Client-Server Architecture 

 OpenGL ES as a Graphics Pipeline 

 OpenGL ES Versions and Renderer Architecture 

 OpenGL ES 3.0 

 OpenGL ES Shading Language Version 3.0 

 Multiple Render Targets 

 Transform Feedback 

 OpenGL ES 2.0 

 OpenGL ES 1.1 

 Designing a High-Performance OpenGL ES App 

 Avoid Synchronizing and Flushing Operations 

 Using glFlush Effectively 

 Avoid Querying OpenGL ES State 

 Use OpenGL ES to Manage Your Resources 

 Use Double Buffering to Avoid Resource Conflicts 

 Be Mindful of OpenGL ES State 

 Encapsulate State with OpenGL ES Objects 

 Organize Draw Calls to Minimize State Changes 

 Tuning Your OpenGL ES App 

 Debug and Profile Your App with Xcode and Instruments 

 Watch for OpenGL ES Errors in Xcode and Instruments 

 Annotate Your OpenGL ES Code for Informative Debugging and Profiling 

 General Performance Recommendations 

 Redraw Scenes Only When the Scene Data Changes 

 Disable Unused OpenGL ES Features 

 Simplify Your Lighting Models 

 Use Tile-Based Deferred Rendering Efficiently 

 Avoid Logical Buffer Loads and Stores 

 Use Hidden Surface Removal Effectively 

 Group OpenGL ES Commands for Efficient Resource Management 

 Minimize the Number of Drawing Commands 

 Use Instanced Drawing to Minimize Draw Calls 

 Minimize OpenGL ES Memory Usage 

 Be Aware of Core Animation Compositing Performance 

 Best Practices for Working with Vertex Data 

 Simplify Your Models 

 Avoid Storing Constants in Attribute Arrays 

 Use the Smallest Acceptable Types for Attributes 

 Use Interleaved Vertex Data 

 Avoid Misaligned Vertex Data 

 Use Triangle Strips to Batch Vertex Data 

 Use Vertex Buffer Objects to Manage Copying Vertex Data 

 Buffer Usage Hints 

 Consolidate Vertex Array State Changes Using Vertex Array Objects 

 Map Buffers into Client Memory for Fast Updates 

 Best Practices for Working with Texture Data 

 Load Textures During Initialization 

 Use the GLKit Framework to Load Texture Data 

 Reduce Texture Memory Usage 

 Compress Textures 

 Use Lower-Precision Color Formats 

 Use Properly Sized Textures 

 Combine Textures into Texture Atlases 

 Use Mipmapping to Reduce Memory Bandwidth Usage 

 Use Multitexturing Instead of Multiple Passes 

 Best Practices for Shaders 

 Compile and Link Shaders During Initialization 

 Check for Shader Program Errors When Debugging 

 Use Separate Shader Objects to Speed Compilation and Linking 

 Respect the Hardware Limits on Shaders 

 Use Precision Hints 

 Perform Vector Calculations Lazily 

 Use Uniforms or Constants Instead of Computing Values in a Shader 

 Use Branching Instructions with Caution 

 Eliminate Loops 

 Avoid Computing Array Indices in Shaders 

 Be Aware of Dynamic Texture Lookups 

 Fetch Framebuffer Data for Programmable Blending 

 Using Framebuffer Fetch in GLSL ES 1.0 

 Using Framebuffer Fetch in GLSL ES 3.0 

 Use Textures for Larger Memory Buffers in Vertex Shaders 

 Concurrency and OpenGL ES 

 Deciding Whether You Can Benefit from Concurrency 

 OpenGL ES Restricts Each Context to a Single Thread 

 Strategies for Implementing Concurrency in OpenGL ES Apps 

 Multithreaded OpenGL ES 

 Perform OpenGL ES Computations in a Worker Task 

 Use Multiple OpenGL ES Contexts 

 Guidelines for Threading OpenGL ES Apps 

 Appendix A: Adopting OpenGL ES 3.0 

 Checklist for Adopting OpenGL ES 3.0 

 Updating Extension Code 

 Remove Extension Suffixes 

 Modify Use of Extension APIs 

 Working with Texture Formats 

 Mapping Buffer Objects into Client Memory 

 Discarding Framebuffers 

 Using Multisampling 

 Continue Using Most Other Extensions in OpenGL ES 3.0 

 Adopting OpenGL ES Shading Language version 3.0 

 Appendix B: Xcode OpenGL ES Tools Overview 

 Using the FPS Debug Gauge and GPU Report 

 Capturing and Analyzing an OpenGL ES Frame 

 Touring the OpenGL ES Frame Debugger 

 Navigator Area 

 View Frame By Call 

 View Frame By Program 

 Editor Area 

 Previewing Framebuffer Contents 

 Editing Shader Programs 

 Inspecting Vertex Data 

 Viewing Textures or Renderbuffers 

 Debug Area 

 The All GL Objects View 

 The Bound GL Objects View 

 The GL Context View 

 The Context Info View 

 The Auto View 

 Appendix C: Using texturetool to Compress Textures 

 texturetool Parameters 

 Appendix D: OpenGL ES 3.0 for Apple A7 GPUs and Later 

 Best Practices 

 Considerations 

 Revision History 

 Glossary 
