# Moogfest 2016

## Designing Audio Visual Systems & Control Hierarchies


Explore how to create real-time synthesis engines to drive graphics in this workshop with Cullen Miller. Using Eurorack and Pure Data, an open-source visual programing environment, participants learn a variety of modular synthesis techniques and ways to communicate with other visual programing environments. By using control hierarchies, digital signal processing, FFT analysis, and computer networks, participants create richer and more responsive visuals with modular synthesis.

All skill levels welcome; however some proficiency with programming is recommended. 
Bring a laptop with TouchDesigner & Pure Data to participate.

** If you successfully register for this workshop, please plan to arrive at least 15 minutes prior to the beginning of the session. Those not in attendance 5-minutes before the session begins, may forfeit their spot to the next person on the waitlist.



## TouchDesigner Data Types (*CHOPs, TOPs, SOPs, DATs, COMPs*) 

		CHOPs (Devices, Control, Animation, Data Analysis, Audio) {

			// Getting data from devices (midi, keyboard, kinect, leap, dmx, serial, mouse, oculus...)

			// Controlling devices (serial, osc, midi, dmx, laser...)

			// Time-based animation - of geometric shapes, images, … puppeteering

			  ++ Smoothing noisy signals
			  ++ normalizing data
			  ++ processing motion (*)
			  ++ controlling movies
			  ++ Timing events, state machines, counting
			  ++ blending pre-made motion channels
			  ++ procedurally-generated motion (lfo, loops, beat, ...)
			  ++ capturing gestures

			// Non-time-based data manipulation

			  ++ Pre-shaping numerical data
			  ++ Analyzing data - from images etc
			  ++ Intermediary holder of data for instancing, DATs...

			// Audio

			  ++ processing from files
			  ++ processing from live audio streams
			  ++ synthesis generation
			  ++ mixing and effects
			  }

		TOPs (Textures Data, Generators, Filters, Compositing, UI) {

			// 2D image data 
			// processed on GPU
			// generators and filters
			// real-time compositing
			// control panel elements

		}

		SOPs (Surfaces, 3D Geometry, 3D Operations) {

			// Surfaces

				++ polygons
				++ curves 
				++ NURBS 
				++ surfaces
				++ metaballs
				++ particles

			// 3D Geometry

				++ generate 
				++ import
				++ modify 
				++ combine

			// 3D Operations

		}

		DATs () {

			// hold sample text

			// hold tables (rows and columns) of strings

			// hold OpenGL shaders

			// JSON, XML, other

			// python scripts

				  ++ raw scripts, modules, callbacks

			// act on changing data using python

			// intermediate format to SOPs, CHOPs

				  ++ insight, transcoding, manipulation

			// respond to message events and sending messages

				  ++ protocols from/to other processes (tcp/ip, udp, websockets, http)
				  ++ protocols from/to devices (multi-touch, MIDI, OSC
				  
				  	> Getting data from devices (midi, keyboard, artnet, serial, osc, tuio...)
						> Controlling devices (serial, osc, midi, laser...)

				  ++ from the TouchDesigner UI (panel, multitouch)
				  ++ from Windows

			// other

				  ++ describing user UI
				  ++ holding application data
				  ++ exporting from DATs
				  ++ getting external data - monitors, file system files/folders

			// used inside TouchDesigner
			
				  ++ defines UI
		}
