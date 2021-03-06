DigiTecK3D Procedural Shader Library
=====================================================================================
Copyright (c) 2013 DigiTecK3D. All Rights Reserved.

Author: Miguel A Santiago Jr.
Web: www.digiteck3d.com
Email: miguel@digiteck3d.com

Contributors
-----------------

- Jens Kafitz | Web: www.campi3d.com | Email: info@campi3d.com

License
-----------------

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,
this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors
may be used to endorse or promote products derived from this software without
specific prior written permission.

This Software Is Provided By The Copyright Holders And Contributors "as Is"
and Any Express Or Implied Warranties, Including, But Not Limited To, The
implied Warranties Of Merchantability And Fitness For A Particular Purpose
are Disclaimed. In No Event Shall The Copyright Holder Or Contributors Be
liable For Any Direct, Indirect, Incidental, Special, Exemplary, Or
consequential Damages (including, But Not Limited To, Procurement Of
substitute Goods Or Services; Loss Of Use, Data, Or Profits; Or Business
interruption) However Caused And On Any Theory Of Liability, Whether In
contract, Strict Liability, Or Tort (including Negligence Or Otherwise)
arising In Any Way Out Of The Use Of This Software, Even If Advised Of He
possibility Of Such Damage.

Info
-----------------

This is a Mari procedural library that adds new procedural types like Cellular, Gabor,
Perlin, Value, Simplex, Brownian, Turbulence, Inigo Multi-Fractal, Ridged Fractal noise and
more planned for the future. This isn't simply just a shader library that adds new nodes
to Mari, but overall adds new functionality to the shader API that other shader writers
can access and modify to create there own shaders from the various new noise functions
added in code to the Mari shader API. Currently the library adds a totally new GPU
noise library from the great work of Brian Sharpe, which is far more efficient and accurate
than the standard noise library. This is the core of the library that allows to implement
various other standard noise functions that are normally found in basic procedural libraries.
The library also finally adds back in the full featured cellular noise function with various
feature sets to mimic organic cellular patterns. Along with these new additions the library
also introduces a port of the Gabor noise function into the library, This is a special type
of noise with anisotropic noise properties.

Best of all the library will fall into the open source domain under the GNU General Public
License and will include all of the source code for you to modify, learn, or just continue
to improve and add to it yourself. So you are free to do with it what you will.

Installation
-----------------

Take scripts and put them into your user preference script directory. Or any startup
script path that Mari has set. Once these are in place, Mari on startup will run through
the scripts folder and load the procedural library. Going to the Python tab and showing
the console will allow you to see the modules loading up. This is where if in any case
the loading fails it will let you know.

Example:
	� On Linux: /Mari/Scripts/
	� On Windows: Documents/Mari/Scripts/

History
-----------------

- 10/15/13		Initial release of the Mari Procedural Library.
- 12/14/13		Release of 1.06 of DT3D Procedural Node Library,
				Intergration of mari.ideascale library,
				Final Python and Folder Structure for mari.ideascale.com,
				Exponential Frequency Growth,
				Flow Paintable Gabor Noise
- 02/08/14    	Released with new Autoloader Structure and Loader Scripts
- 06/16/14		Changed over to a BSD license format in the library
