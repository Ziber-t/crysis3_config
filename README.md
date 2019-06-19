# Crysis 3 config ULTRA grahics
Config for Crysis3 with HD(max) graphic

<html>
<head>
<meta name="Keywords" content="Crysis 3, ultra grahic">
<title>Crysis 3 Crysis 3 config ULTRA grahics Help</title>

</head>
<body>

<p>This help file contains the cvar names and details available in Crysis 3.</p>
<h1>Gameplay</h1>



![alt Screen](https://github.com/Ziber-t/crysis3_config/raw/master/screenShots/Screen3.jpg)
=======================================================================================
![alt Screen](https://github.com/Ziber-t/crysis3_config/raw/master/screenShots/Screen2.jpg)
=======================================================================================
![alt Screen](https://github.com/Ziber-t/crysis3_config/raw/master/screenShots/Screen1.jpg)
=======================================================================================
![alt Screen](https://github.com/Ziber-t/crysis3_config/raw/master/screenShots/Screen4.jpg)
=======================================================================================
![alt Screen](https://github.com/Ziber-t/crysis3_config/raw/master/screenShots/Screen5.jpg)
=======================================================================================
<h3>Field of View</h3>
<p>CVar: <code>cl_fov</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>The vertical field of view in degrees.<br />This controls several individual FOV controls That you can tweak manually if you prefer:<br /><br />cl_FOV - The main field of view<br />r_DrawNearFOV - the field of view for nearby objects (held weapon, etc)<br />pl_movement.power_sprint_targetFOV - The field of view while power sprinting<br /><br />Default Value: 60</p>

<h3>HUD Bobbing</h3>
<p>CVar: <code>cl_bobhud</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Controls the amount of bob hud which is applied.<br /><br />Default is 1.0</p>

<h3>HUD Canvas Adjustment</h3>
<p>CVar: <code>hud_canvas_width_adjustment</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Multiplayer only. Multiplies the width of the HUD's virtual canvas in cases where it may overlap monitor boundaries in multi-monitor setups. NOTE: before this multiplier is applied, the HUD clamps itself to a 16:9 res.<br /><br />Default is 1.0</p>

<h3>Hud Hide</h3>
<p>CVar: <code>hud_hide</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>If this cvar is true the HUD will be hidden from view completely.<br /><br />Suitable for screenshots or very immersive play. NOTE: This feature is not fully supported, and this cvar value might need to be reset in game, e.g. on loading a save.<br /><br />Default is off (hud visible)</p>

<h3>Music Volume</h3>
<p>CVar: <code>s_MusicVolume</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Controls the volume of Music, in the range from 0.0 to 1.0.<br /><br />Default is 1.0, full volume.</p>

<h3>SFX Volume</h3>
<p>CVar: <code>s_SFXVolume</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Controls the volume of SFX, in the range from 0.0 to 1.0.<br /><br />Default is 1.0, full volume.</p>

<h3>Dialog Volume</h3>
<p>CVar: <code>s_DialogVolume</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Controls the volume of Dialog, in the range from 0.0 to 1.0.<br /><br />Default is 1.0, full volume.</p>

<h3>Max FPS Limit</h3>
<p>CVar: <code>sys_MaxFps</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Limits the frame rate to specified number.<br /><br />A value of 0 means no limit.<br /><br />Default is 0</p>

<h1>Input</h1><h3>Toggle Crouch</h3>
<p>CVar: <code>cl_crouchToggle</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Makes the crouch key work as a toggle.<br /><br />Default is on</p>

<h3>Toggle Zoom</h3>
<p>CVar: <code>cl_zoomToggle</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Makes the zoom key work as a toggle.<br /><br />Default is on</p>

<h3>Mouse Smoothing</h3>
<p>CVar: <code>i_mouse_smooth</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Set mouse smoothing value, also if 0 (disabled) there will be a simple average between the old and the actual input.<br /><br />(1.0 = very very smooth, 30 = almost instant)<br /><br />Default is 0.0</p>

<h3>Mouse Acceleration</h3>
<p>CVar: <code>i_mouse_accel</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Set mouse acceleration, 0.0 means no acceleration.<br /><br />Default is 0.0</p>

<h3>Mouse Acceleration Max</h3>
<p>CVar: <code>i_mouse_accel_max</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Set mouse max mouse delta when using acceleration.<br /><br />Default is 100.0</p>

<h3>Mouse Sensitivity</h3>
<p>CVar: <code>cl_sensitivity</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Sets mouse sensitivity.<br /><br />Default is 30.0</p>

<h3>ADS Sensitivity Multiplier</h3>
<p>CVar: <code>cl_sensitivityMultiplierADS</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>This is a multiplier on top of the existing scope multiplier.<br />If you want weapons to be generally more responsive when in ADS, make this >1.0.<br />If you want them less responsive, make it <1.0.<br /><br />Default is 1.0</p>

<h3>ADS Sensitivity Override</h3>
<p>CVar: <code>cl_sensitivityOverrideADS</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>this is a multiplier that ignores the existing scope multipliers.<br />It's a flat override. This should always be <1.0.<br /><br />Default is 1.0, <= 0.0 uses defaults</p>

<h1>Graphics Features</h1><h3>Particle Collisions</h3>
<p>CVar: <code>e_ParticlesObjectCollisions</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls what objects particles will collide with.<br /><br />Default Value: Static (Low/Medium), Dynamic (High/Very High)<br /><br />None: No particle collisions at all.<br />Static: Particles tagged for collisions will interact with static objects.<br />Dynamic: As with Static, but dynamic objects also.<br /></p>

<h3>Particle Motion Blur</h3>
<p>CVar: <code>e_ParticlesMotionBlur</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables motion blur effect on fast moving particles.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Force Soft Particles</h3>
<p>CVar: <code>e_ParticlesForceSoftParticles</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Forces all possible particles to use soft intersections with geometry - increases the cost but will all but eliminate hard edges on particles.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Tessellation</h3>
<p>CVar: <code>e_Tessellation</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables DX11 ALL tessellation.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)<br /><br />NOTE: Currently not tweakable in the latest build of the game.<br />Will be tweakable soon.</p>

<h3>Water Ocean Tessellation</h3>
<p>CVar: <code>r_WaterTessellationHW</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables DX11 tessellation for the ocean water surface.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Water Caustics</h3>
<p>CVar: <code>r_WaterCaustics</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables ALL water caustics.<br /><br />Default Value: On</p>

<h3>Water Volume Caustics</h3>
<p>CVar: <code>r_WaterVolumeCaustics</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables water caustics on water volumes.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Pixel Accurate Displacement Maps</h3>
<p>CVar: <code>r_SilhouettePOM</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the Pixel Accurate Displacement Mapping (VERY GPU intensive).<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Real-time Global Illumination</h3>
<p>CVar: <code>e_GI</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables real-time Global Illumination.<br /><br />Default Value: Off (Low), On (Medium/High/Very High)</p>

<h3>Real-time Volumetric Cloud Shadows</h3>
<p>CVar: <code>r_FogShadows</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables Real-time Volumetric Cloud Shadows.<br /><br />Default Value: Off (Low/Medium), On (High/Very High)</p>

<h3>Volumetric Water Shadows</h3>
<p>CVar: <code>r_FogShadowsWater</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the Real-time Volumetric Shadows underneath water.<br /><br />Default Value: Off (Low), On (Medium/High/Very High)</p>

<h3>Volumetric Beams</h3>
<p>CVar: <code>r_Beams</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Toggles volumetric light beams.<br /><br />Default Value: Off (Low/Medium), On (High/Very High)</p>

<h3>Sun shafts (Godrays)</h3>
<p>CVar: <code>r_Sunshafts</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Toggles Sun shafts.<br /><br />Default Value: On</p>

<h3>Screen-space Reflections</h3>
<p>CVar: <code>r_SSReflections</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the Screen-Space reflections effect on glossy or reflective materials.<br /><br />Default Value: Off (Low/Medium/High), On (Very High)</p>

<h3>Depth of Field</h3>
<p>CVar: <code>r_DepthOfField</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the depth of field blur effect.<br /><br />Default Value: OnNOTE: Currently not tweakable in the latest build of the game.<br />Will be tweakable soon.</p>

<h3>Explosion Blur</h3>
<p>CVar: <code>g_radialBlur</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the radial blur effect applied after an explosion.<br /><br />Default Value: On</p>

<h3>Color Grading</h3>
<p>CVar: <code>r_ColorGrading</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Enables or disables the artist controlled color grading post-processing effect.<br /><br />Default Value: On</p>

<h1>Graphics Tweaking</h1><h3>Sharpening</h3>
<p>CVar: <code>r_Sharpening</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the level of the post-processing image sharpening filter.<br />Higher values give more sharpening, but too high values will create artifacts<br />A value of 0.0 is off<br /><br />Default Value: 0.25<br /><br /></p>

<h3>Chromatic Aberration</h3>
<p>CVar: <code>r_ChromaticAberration</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the level of the post-processing chromatic aberration.<br /><br />A value of 0.0 is off<br /><br />Default Value: 1.5<br /><br /></p>

<h3>Filmgrain</h3>
<p>CVar: <code>r_HDRGrainAmount</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the level of film grain applied to the final image to help alleviate artifacts from lack of colour precision in 32-bit colour displays.<br /><br />A value of 0.0 is off<br /><br />Default Value: 0.0<br /><br /></p>

<h3>Bloom amount</h3>
<p>CVar: <code>r_HDRBloomRatio</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the level of bloom used to simulate over-bright areas of the screen<br /><br />Default Value: 0.15<br /><br /></p>

<h3>Bloom threshold</h3>
<p>CVar: <code>r_HDRBrightLevel</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the brightness level threshold used to compute bloom<br /><br />Default Value: 1.0<br /><br /></p>

<h3>Ambient Occlusion Method</h3>
<p>CVar: <code>r_ssao</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Chooses the ambient occlusion method<br /><br />Default Value: SSAO (Low/Medium/High), SSDO (Very High)<br /><br />None: No ambient occlusion is used. (r_ssao = 0, r_ssdo = 0)<br />SSAO: Screen-space Ambient Occlusion. (r_ssao = 3, r_ssdo = 0)<br />SSDO: Screen-space Directional Occlusion. (r_ssao = 0, r_ssdo = 2)</p>

<h3>SSAO Amount</h3>
<p>CVar: <code>r_SSAOAmount</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls how much SSAO affects ambient lighting.<br />NOTE: Only affects SSAO, not SSDO.<br /><br />Default Value: 1.0</p>

<h3>SSAO Quality</h3>
<p>CVar: <code>r_SSAOQuality</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls SSAO quality.<br />NOTE: Only affects SSAO, not SSDO.<br /><br />Default Value: 0 (Low), 1 (Medium), 2 (High), 3 (Very High)</p>

<h3>Half-resolution SSAO</h3>
<p>CVar: <code>r_SSAODownscale</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Perform SSAO calculations at half-resolution for performance.<br /><br />NOTE: Only affects SSAO, not SSDO.<br /><br />Default Value: On (Low/Medium), Off (High/Very High)</p>

<h3>SSDO Radius</h3>
<p>CVar: <code>r_SSDORadius</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>SSDO processing radius.<br /><br />Default Value: 0.4</p>

<h3>SSDO Directional Strength</h3>
<p>CVar: <code>r_SSDOAmount</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Strength of the SSDO directional occlusion.<br /><br />Default Value: 0.8</p>

<h3>SSDO Ambient Strength</h3>
<p>CVar: <code>r_SSDOAmbientAmount</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Strength of the SSDO ambient occlusion.<br /><br />Default Value: 1.1</p>

<h3>Screenspace Reflection Cutoff</h3>
<p>CVar: <code>r_SSReflCutoff</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Glossiness value below which Screenspace reflections are disabled.<br /><br />Default Value: 0.1</p>

<h3>Screenspace Reflection Exponent</h3>
<p>CVar: <code>r_SSReflExp</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Reflection exponent, applied to glossiness material property.<br /><br />Default Value: 0.25</p>

<h3>Texture Pool Size (MB)</h3>
<p>CVar: <code>r_TexturesStreamPoolSize</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Sets the size of VRAM that is available in a pool for texture streaming.<br />Value is in Megabytes, and may be clamped based on the amount of video memory detected<br /><br />Default Value: 192 (Low), 384 (Medium), 512 (High/Very High)<br /><br /></p>

<h3>Water Caustics Density</h3>
<p>CVar: <code>r_WaterVolumeCausticsDensity</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Density/resolution of watervolume caustic grid.<br /><br />Default Value: 64 (Low), 128 (Medium), 256 (High/Very High)</p>

<h3>Water Caustics Resolution</h3>
<p>CVar: <code>r_WaterVolumeCausticsRes</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Resolution of watervolume caustics texture.<br /><br />Default Value: 384 (Low), 512 (Medium), 1024 (High/Very High)</p>

<h3>Water Caustics Max Distance</h3>
<p>CVar: <code>r_WaterVolumeCausticsMaxDist</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Maximum distance at which caustics are visible.<br /><br />Default Value: 20 (Low), 25 (Medium), 35 (High/Very High)</p>

<h3>Shadow Timeslicing</h3>
<p>CVar: <code>e_GsmCache</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Saves GPU performance by updating distant shadows less often.<br /><br />Default Value: On (Low) Off (Medium/High/Very High)</p>

<h3>Shadow First Timesliced LOD</h3>
<p>CVar: <code>e_GsmCacheLodOffset</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Determines which LOD will timeslice (every LOD after will also timeslice).<br />Higher values will mean fewer LODs will be timesliced.<br /><br />Default Value: 3</p>

<h3>Shadow Casting Light Scale</h3>
<p>CVar: <code>e_ShadowsResScale</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the resolution of shadow maps used for individual shadow casting lights.<br />Value is an arbitrary multiplier, so doubling this will double the resolution of each light<br /><br />Default Value: 3.4 (Low/Medium/High), 40 (Very High)<br /><br /></p>

<h3>Tessellated Shadow Cascades</h3>
<p>CVar: <code>e_ShadowsTessellateCascades</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Determines how many shadow cascades to apply tessellation for.<br />A setting of 0 disables tessellation in all shadows.<br /><br />Default Value: 1<br /><br />NOTE: Currently not tweakable in the latest build of the game.<br />Will be tweakable soon.</p>

<h3>Shadow Pool Size</h3>
<p>CVar: <code>e_ShadowsPoolSize</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Sets the size of the shadow pool render target - increased size produces more resolution available for, and fewer artifacts in shadow casting lights (NOT including the sun). Value should be a power of 2 (128, 256, ...)<br />If the pool is too small to fit the minimum size for the shadow casting lights, the GPU will thrash and performance will be severely impacted<br /><br />Default Value: 2048 (Low/Medium/High), 4096 (Very High)<br /><br /></p>

<h3>Sun Shadow Map Size</h3>
<p>CVar: <code>e_ShadowsMaxTexRes</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Sets the size of each sun shadow cascade - increased size produces more resolution available for sun shadows.<br /><br />Default Value: 512 (Low), 1024 (Medium/High/Very High)<br /><br /></p>

<h3>Global Illumination Timeslicing</h3>
<p>CVar: <code>e_GICache</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Sets the number of frames to cache GI results for before regenerating<br />A value of 0 disables all caching and regenerates GI every frame<br /><br />Default Value: 7<br /><br /></p>

<h3>Global Illumination Iterations</h3>
<p>CVar: <code>e_GIIterations</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Sets the number of iterations to perform when calculating Global Illumination<br />A higher number will reduce bleeding and lengthen the light propagation distance<br /><br />Default Value: 10<br /><br /></p>

<h3>Tessellation Distance Limit</h3>
<p>CVar: <code>e_TessellationMaxDistance</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Changes the distance in metres where tessellation will stop applying to objects<br /><br />Default Value: 30<br /><br /></p>

<h3>Tessellation Triangle Target Size</h3>
<p>CVar: <code>r_TessellationTriangleSize</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>The length of a triangle edge in pixels to aim for when tessellating.<br /><br />Default Value: 8<br /><br /></p>

<h3>Grass Instance Animation Distance</h3>
<p>CVar: <code>e_MergedMeshesInstanceDist</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Distance fudge-factor where interactive grass instances will stop animating.<br /><br />Default Value: 4.5 (Low/Medium/High) 8.0 (Very High)<br /><br /></p>

<h3>Grass Instance Max Distance</h3>
<p>CVar: <code>e_MergedMeshesViewDistRatio</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Multiplier controlling where chunks of interactive grass instances will disappear in the distance.<br /><br />Default Value: 50<br /><br /></p>

<h3>LOD distance ratio</h3>
<p>CVar: <code>e_LodRatio</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls how close objects drop to lower Levels Of Detail. A higher number means a longer distance before this drop happens.<br /><br />Default Value: 4 (Low), 6 (Medium) 20 (High), 40 (Very High)<br /><br /></p>

<h3>View distance ratio (General)</h3>
<p>CVar: <code>e_ViewDistRatio</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls how close objects will stop rendering in the distance.<br /><br />Default Value: 25 (Low), 35 (Medium) 100 (High/Very High)<br /><br /></p>

<h3>View distance ratio (Vegetation)</h3>
<p>CVar: <code>e_ViewDistRatioVegetation</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls how close vegetation will stop rendering in the distance.<br /><br />Default Value: 21 (Low), 31 (Medium) 100 (High/Very High)<br /><br /></p>

<h3>View distance ratio (Detail)</h3>
<p>CVar: <code>e_ViewDistRatioDetail</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls how close certain objects marked as 'detail' by artists will stop rendering in the distance.<br /><br />Default Value: 19 (Low), 24 (Medium) 100 (High/Very High)<br /><br /></p>

<h1>Miscellaneous</h1><h3>Skip Intro Movies</h3>
<p>CVar: <code>g_skipIntro</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Skips the introduction movies that play before the main menu at game boot.<br /><br />Default Value: Off</p>

<h3>Fullscreen window mode</h3>
<p>CVar: <code>r_FullscreenWindow</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>When enabled, selecting 'fullscreen' in the menus will use a window that fills the screen, allowing easy alt-tab.<br />Windowed mode will behave as normal.<br /><br />Default Value: Off</p>

<h3>Disallow Fullscreen Pre-emption</h3>
<p>CVar: <code>r_FullscreenPreemption</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>When enabled, Pop-ups such as instant message windows and other focus-stealing windows will not minimise the game.<br /><br />Default Value: On</p>

<h3>Multiplayer Loading Screen Timeout</h3>
<p>CVar: <code>g_mpLoaderScreenMaxTime</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Max time in seconds that the multiplayer loading screen is allowed to wait<br />before timing out and aborting multiplayer<br /><br />Default Value: 25.0f</p>

<h3>AMD HD3D</h3>
<p>CVar: <code>r_StereoAMD3D</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Forces on hardware use of AMD HD3D output.<br /><br />Default Value: Disabled<br /><br />Disabled: side-by-side and other modes are available via menus.<br />Enabled: If support is detected, AMD HD3D output will be enabled regardless of menu options.</p>

<h3>3D Stereo Strength</h3>
<p>CVar: <code>r_StereoStrength</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Multiplier which influences the strength of the stereo effect<br /><br />Default Value: 1.0f</p>

<h3>3D Stereo Separation</h3>
<p>CVar: <code>r_StereoEyeDist</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Maximum separation between stereo images in percentage of the screen<br /><br />Default Value: 0.02f</p>

<h3>3D Stereo Convergance Distance</h3>
<p>CVar: <code>r_StereoScreenDist</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Distance to plane where stereo parallax converges to zero<br /><br />Default Value: 0.25f</p>

<h3>3D Stereo Gun Scale</h3>
<p>CVar: <code>r_StereoNearGeoScale</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Scale for near geometry (weapon) that gets pushed into the screen<br /><br />Default Value: 0.65f</p>

<h3>3D Stereo HUD Distance</h3>
<p>CVar: <code>r_StereoHudScreenDist</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Distance to plane where hud stereo parallax converges to zero<br /><br />Default Value: 0.5f</p>

<h3>Multi-GPU Support</h3>
<p>CVar: <code>r_MultiGPU</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Determines Multi-GPU support in engine.<br /><br />Default Value: Autodetect<br /><br />Disabled: No multi-GPU support.<br />Forced: Multi-GPU support is force-enabled.<br />Autodetect: CryEngine auto-detects whether or not to enable Multi-GPU support.<br /></p>

<h3>Multi-Monitor Support</h3>
<p>CVar: <code>r_3MonMode</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Determines Multi-Monitor support in engine. e.g. Moving HUD to centre monitor<br /><br />Default Value: Autodetect<br /><br />Disabled: No explicit multi-Monitor support.<br />Forced: Multi-Monitor support is force-enabled.<br />Autodetect: CryEngine auto-detects whether or not to enable Multi-Monitor support.<br /></p>

<h3>Multi-Monitor HUD Tweak</h3>
<p>CVar: <code>r_3MonModeCGFOffset</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Adds position offset in X direction to all HUD objects. Allows fine tuning of HUD placement<br /><br />Default Value: 1.25f</p>

<h3>Force Output Adapter</h3>
<p>CVar: <code>r_overrideDXGIAdapter</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Gives the number of graphics card to use when initialising CryEngine. NOTE: IF SET THIS WILL OVERRIDE CRYENGINE DETECTION. Leave unset unless the game will not boot and detects the wrong graphics card for you.<br /><br />Default Value: N/A</p>

<h3>Force Output Monitor</h3>
<p>CVar: <code>r_overrideDXGIOutput</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Gives the number of display to use when creating the game window. 0 is the default/primary monitor and 1, 2, etc are displays after that. Allows you to create the window on a different monitor from your primary monitor (e.g. a TV or other external display)<br /><br />Default Value: 0</p>

<h3>Hardware Gamma Level</h3>
<p>CVar: <code>r_Gamma</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Changes the hardware gamma level. Affects desktop as well.<br /><br />Default Value: 1.0</p>

<h3>Internal Occlusion Culling</h3>
<p>CVar: <code>e_CoverageBufferReproj</code></p>
<p>Recommended to be placed in <code>autoexec.cfg</code></p>
<p>Controls the internal occlusion culling. You shouldn't need to modify this cvar, but if you encounter any popping with rapid moving, experiment with disabling this.<br /><br />Default Value: On</p>

<h3>Game Network Port</h3>
<p>CVar: <code>g_blaze_gamePort</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>The network port games connections will be made on.</p>

<h3>Enable Blaze VOIP</h3>
<p>CVar: <code>net_blaze_voip_enable</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Toggles whether Blaze VOIP is enabled or not.<br /><br />Default Value: On</p>

<h3>Enable Blaze VOIP PTT</h3>
<p>CVar: <code>net_blaze_voip_enable_ptt</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Toggles whether Blaze VOIP Push-to-talk is enabled or not.<br /><br />Default Value: On</p>

<h3>Enable Blaze VOIP</h3>
<p>CVar: <code>net_blaze_voip_playback_volume</code></p>
<p>Recommended to be placed in <code>system.cfg</code></p>
<p>Sets the Blaze VOIP playback volume, in the range 0.0 to 1.0.<br /><br />Default Value: 1.0 Full volume</p>

<h1>Advanced</h1><p>There are two available commands that allow advanced use of the cvar system.
<br />
<br />bind (x) (commands...)
<br />
<br />You can execute the 'bind' command to tie a given set of commands to a keypress. For example "bind o cl_fov 70" will change the FOV to 90 when you press the o key. "bind p cl_fov 80" will then do the same for the 'p' key. Then you can toggle between these FOVs.
<br />
<br />You can also specify multiple commands separated by ;s. For example "bind o cl_fov 70; r_drawnearfov 70" will change both cvars to 90 when you press the o key.
<br />
<br />Also supported are modifiers like so:
<br />
<br />bind "alt o" cl_fov 70
<br />
<br />The modifier must be specified in ""s.
<br />
<br />exec (filename.cfg)
<br />
<br />Exec allows you to predefine many console commands in a .cfg file (next to autoexec.cfg for example), which are then executed all at once with just one command in game. The file is read each time so it can be modified and re-exec'd to change any settings, similar to how cvars can be modified in real-time in game.
<br />
<br />Combining this with bind above can allow you to change many settings at the same time easily.</p></body></html>


=====================================================================================

<h1>Тонкая настройка игры (RUS)</h1>


<div class="post-entry">
<p>Кончено Crysis 3 можно настроить и через меню настройки, но настоящие профи настраивают свой Crysis 3 через консольные команды. Electronic Arts предоставили полны список консольных команд тонкой настройки GPU для Crysis 3. Команды тонкой настройки могут быть введены во время однопользовательской игры через консоль вызываемую тильдой «~», кто не в курсе — это такой значок над клавишей Tab в английской раскладке клавиатуры.</p>
<p>Вместе с командами предоставлена инструкция по их редактированию. По большей части их лучше разместить в конфигурационном файле (файл с расширением .cfg) в корневой директории Crysis 3. Но если вы хотите получить быстрое изменение то любая из этих команд точно так же будет работать и в консоле. Например, для снятия скриншота в Crysis 3 вы можете удалить все визуальные помехи используя следующие команды:</p>
<p>r_colorgrading 0 (Удаляет чёрную и белую цветокоррекцию)<br>
hud_hide 1 (Удаляет HUD)<br>
r_drawnearfov 2 (Переключает видимость оружия)</p>
<p>Полный список команд приведён ниже. Он просто огромного размера. В скобках указаны настройки графики (Низкие/Средние/Высокие/Очень Высокие).</p>
<h3>Тонкая настройка игры Crysis 3</h3>
<p><strong> Поле зрения</strong><br>
CVar: cl_fov<br>
Рекомендует разместить в system.cfg<br>
Вертикальный угол обзора в градусах.<br>
Это опция контролирует несколько отдельных элементов управления, которые вы можете настроить вручную<br>
cl_FOV — основное поле зрения<br>
r_DrawNearFOV — поле зрения близлежащих объектов (оружие и т. д.)<br>
pl_movement.power_sprint_targetFOV — поле зрения во время спринта<br>
Значение по умолчанию: 60</p>
<p><strong>Множитель HUD</strong><br>
CVar: hud_canvas_width_adjustment<br>
Рекомендует разместить в system.cfg<br>
Только для мультиплеера. Множитель ширины HUD для тех случаев, когда перекрываются границы экрана в системе с несколькими мониторами.<br>
ПРИМЕЧАНИЕ: Перед изменением значения множителя установите соотношение сторон HUD в 16:9.<br>
Значение по умолчанию: 1</p>
<p><strong>Скрыть HUD</strong><br>
CVar: hud_hide<br>
Рекомендуется разместить в system.cfg<br>
Если значение этой переменной выставлено в true, то HUD скрыт.<br>
Подходит для снятия скриншотов или захватывающей игры.<br>
ПРИМЕЧАНИЕ: Эта функция поддерживается не полностью и возможно понадобится перезагрузка игры для включения этой переменной.<br>
Значение по умолчанию: off (HUD видимый)</p>
<p><strong>Громкость Музыки</strong><br>
CVar: s_MusicVolume<br>
Рекомендуется разместить в system.cfg<br>
Управляет громкостью музыки в диапазоне от 0,0 до 1,0.<br>
Значение по умолчанию: 1.0 (Полная громкость музыки)</p>
<p><strong>Громкость Спецэффектов</strong><br>
CVar: s_SFXVolume<br>
Рекомендуется разместить в system.cfg<br>
Управляет громкостью спецэффектов в диапазоне от 0,0 до 1,0.<br>
Значение по умолчанию:1.0 (Полная громкость спецэффектов)</p>
<p><strong>Громкость Диалогов</strong><br>
CVar: s_DialogVolume<br>
Рекомендуется разместить в system.cfg<br>
Управляет громкостью диалогов в диапазоне от 0,0 до 1,0.<br>
Значение по умолчанию:1.0 (Полная громкость диалогов)</p>
<p><strong>Ограничение максимального FPS</strong><br>
CVar: sys_MaxFps<br>
Рекомендуется разместить в system.cfg<br>
Ограничивает частоту кадров до указанного числа.<br>
Значение 0 указывает на отсутствие ограничения<br>
Значение по умолчанию: 0</p>
<h4>Тонкая настройка управление Crysis 3</h4>
<p><strong> Переключение приседания</strong><br>
CVar: cl_crouchToggle<br>
Рекомендуется разместить в system.cfg<br>
Делает клавишу приседания переключателем.<br>
Значение по умолчанию: on</p>
<p><strong>Переключение увеличения</strong><br>
CVar: cl_zoomToggle<br>
Рекомендуется разместить в system.cfg<br>
Делает клавишу зума переключателем<br>
Значение по умолчанию: on</p>
<p><strong>Сглаживание мыши</strong><br>
CVar: i_mouse_smooth<br>
Рекомендуется разместить в system.cfg<br>
Устанавливает значение сглаживания мыши, 0 — отключено.<br>
(1.0 = очень очень гладко, 30 = почти мгновенно)<br>
Значение по умолчанию: 0</p>
<p><strong>Ускорение мыши</strong><br>
CVar: i_mouse_accel<br>
Рекомендуется разместить в system.cfg<br>
Значение 0.0 означает без ускорения<br>
Значение по умолчанию: 0.0</p>
<p><strong>Максимальное ускорение мыши</strong><br>
CVar: i_mouse_accel_max<br>
Рекомендуется разместить в system.cfg<br>
Устанавливает значение максимальной дельты при использовании ускорения мыши<br>
Значение по умолчанию: 100</p>
<p><strong>Чувствительность мыши</strong><br>
CVar: cl_sensitivity<br>
Рекомендуется разместить в system.cfg<br>
Устанавливает чувствительность мыши<br>
Значение по умолчанию: 30</p>
<h4>Расширенные графические настройки Crysis 3</h4>
<p><strong>Столкновение частиц</strong><br>
CVar: e_ParticlesObjectCollisions<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывает какие частицы будут сталкиваться<br>
Значение по умолчанию: Static (Низкие/Средние), Dynamic (Высокие/Очень Высокие)<br>
None: Отсутствуют столкновения частиц<br>
Static: Частицы будут взаимодействовать со статическими объектами<br>
Dynamic: Как и для Static, но и с динамическими объектами.</p>
<p><strong>Размытие движения частиц</strong><br>
CVar: e_ParticlesMotionBlur<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает эффект размытия на движущихся частицах.<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Принудительное смягчение частиц</strong><br>
CVar: e_ParticlesForceSoftParticles<br>
Рекомендуется разместить в autoexec.cfg<br>
Принудительно для всех частиц будет использоваться смягчённая геометрия. Требуется высокая производительность, но будут смягчены все острые углы у частиц.<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Мозаичность</strong><br>
CVar: e_Tessellation<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает DX11 ALL мозаичность<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)<br>
ПРИМЕЧАНИЕ: В настоящее время не поддерживается игрой, но в ближайшее время будет включена.</p>
<p><strong>Мозаичность воды океана</strong><br>
CVar: r_WaterTessellationHW<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает DX11 ALL мозаичность поверхности воды океана<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Точные карты смещения пикселей</strong><br>
CVar: r_SilhouettePOM<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает точные карты смещения пикселей (Высокая нагрузка на GPU)<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Глобальное освещение в режиме реального времени</strong><br>
CVar: e_GI<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает Глобальное освещение в режиме реального времени<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Объёмные тени облаков в режиме реального времени</strong><br>
CVar: r_FogShadows<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает Объёмные тени облаков в режиме реального времени<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Объёмные тени под водой</strong><br>
CVar: r_FogShadowsWater<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает Объёмные тени под водой в режиме реального времени<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Отражение объектов</strong><br>
CVar: r_SSReflections<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает Отражения глянцевых и светоотражающих материалов в режиме реального времени<br>
Значение по умолчанию: Off (Низкие/Средние/Высокие), On (Очень Высокие)</p>
<p><strong>Глубина резкости</strong><br>
CVar: r_DepthOfField<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает глубину резкости с эффектом размытия<br>
Значение по умолчанию: On<br>
ПРИМЕЧАНИЕ: В настоящее время не поддерживается игрой, но в ближайшее время будет включена.</p>
<p><strong>Размытие взрыва</strong><br>
CVar: g_radialBlur<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает эффект радиального размытия после взрыва<br>
Значение по умолчанию: On</p>
<p><strong>Цветокоррекция</strong><br>
CVar: r_ColorGrading<br>
Рекомендуется разместить в autoexec.cfg<br>
Включает или выключает пост-обработку художественным эффектом цветовой коррекции<br>
Значение по умолчанию: On</p>
<h5>Тонкая настройка графики Crysis 3</h5>
<p><strong> Резкость</strong><br>
CVar: r_Sharpening<br>
Рекомендуется разместить в autoexec.cfg<br>
Регулирует уровень фильтра резкости во время пост-обработки<br>
Более высокие значения повышают резкость, но слишком высоки будут выдавать артефакты<br>
Значение 0,0 — выключена<br>
Значение по умолчанию : 2,5</p>
<p><strong>Хроматическая аберрация</strong><br>
CVar: r_ChromaticAberration<br>
Рекомендуется разместить в autoexec.cfg<br>
Регулирует уровень фильтра хроматическая аберрация во время пост-обработки<br>
Значение 0,0 — выключена<br>
Значение по умолчанию : 1,5</p>
<p><strong>Плёночная зернистость</strong><br>
CVar: r_HDRGrainAmount<br>
Рекомендуется разместить в autoexec.cfg<br>
Регулирует уровень зернистости применяемого к окончательному изображению, что бы убрать артефакты от недостаточной цветопередачи на мониторах с 32-битной цветностью<br>
Значение 0,0 — выключена<br>
Значение по умолчанию : 0,0</p>
<p><strong>Значение выцветания</strong><br>
CVar: r_HDRBloomRatio<br>
Рекомендуется разместить в autoexec.cfg<br>
Регулирует уровень выцветания для имитации сверх-ярких областей на экране<br>
Значение по умолчанию : 0,15</p>
<p><strong>Порог выцветания</strong><br>
CVar: r_HDRBrightLevel<br>
Рекомендуется разместить в autoexec.cfg<br>
Управление порогом уровня яркости для расчёта выцветания в сверх-ярких областях<br>
Значение по умолчанию : 1,0</p>
<p><strong>Метод Ambient Occlusion</strong><br>
CVar: r_ssao<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывает метод Ambient Occlusion<br>
Значение по умолчанию: SSAO (Низкие/Средние/Высокие), SSDO (Очень Высокие)<br>
None: Ambient Occlusion не используется<br>
SSAO: используется Screen-space Ambient Occlusion.<br>
SSDO: используется Screen-space Directional Occlusion.</p>
<p><strong>Размер пула текстур (МБ)</strong><br>
CVar: r_TexturesStreamPoolSize<br>
Рекомендуется разместить в autoexec.cfg<br>
Устанавливает размер видеопамяти доступный пулу текстур<br>
Размер указывается в мегабайтах и может ограничиваться в соответствии с обнаруженным размером видеопамяти<br>
Значение по умолчанию: 192 (Низкие), 384 (Средние), 512 (Высокие / Очень Высокие)</p>
<p><strong>Отключение прорисовки дальних теней</strong><br>
CVar: e_GsmCache<br>
Рекомендуется разместить в autoexec.cfg<br>
Снижает нагрузку на GPU за счёт отключения прорисовки теней дальних объектов<br>
Значение по умолчанию: On (Низкие) Off (Средние/Высокие/Очень Высокие)</p>
<p><strong>Масштабирование каскадов тени от источников света</strong><br>
CVar: e_ShadowsResScale<br>
Рекомендуется разместить в autoexec.cfg<br>
Управляет разрешением карты теней для отдельных источников света.<br>
Значение — произвольный множитель, удвоение которого удвоит разрешение каждого источника света<br>
Значение по умолчанию: 3,4 (Низкие/Средние/Высокие), 40 (Очень Высокие)</p>
<p><strong>Мозаичные каскады тени</strong><br>
CVar: e_ShadowsTessellateCascades<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывает сколько каскадов тени применяться для мозаичности<br>
Значение 0 — отключает всю мозаичность тени<br>
Значение по умолчанию: 1<br>
ПРИМЕЧАНИЕ: В настоящее время не поддерживается игрой, но в ближайшее время будет включена.</p>
<p><strong>Размер пула теней</strong><br>
CVar: e_ShadowsPoolSize<br>
Рекомендуется разместить в autoexec.cfg<br>
Устанавливает размеру пула для редеринга теней — увеличение размера пула позволяет увеличить разрешение и уменьшить количество артефактов теней от источников света (НЕ УЧИТЫВАЯ Солнце). Значение должно быть степенью 2 (128, 256, 512 и т. д.)<br>
Если размер пула слишком мал, что бы соответствовать минимальному размеру карты теней, то нагрузка на GPU сильно возрастёт и пострадает производительность.<br>
Значение по умолчанию: 2048 (Низкие/Средние/Высокие), 4096 (Очень Высокие)</p>
<p><strong>Размер карты теней от Солнца</strong><br>
CVar: e_ShadowsMaxTexRes<br>
Рекомендуется разместить в autoexec.cfg<br>
Устанавливает размер для каждого каскада тени солнца, увеличение значения увеличивает разрешение теней.<br>
Значение по умолчанию: 512 (Низкие), 1024 (Средние/Высокие/Очень Высокие)</p>
<p><strong>Дальность расчёта глобальной освещённости</strong><br>
CVar: e_GICache<br>
Рекомендуется разместить в autoexec.cfg<br>
Устанавливает количество кадров для кэширования результатов расчёта Глобальной Освещённости перед регенерацией<br>
Значение 0 отключает всё кэширование и регенерируется каждый кадр Глобальной Освещённости<br>
Значение по умолчанию: 7</p>
<p><strong>Количество итераций расчёта Глобальной Освещённости</strong><br>
CVar: e_GIIterations<br>
Рекомендуется разместить в autoexec.cfg<br>
Устанавливает количество итераций при выполнении расчёта Глобальной Освещённости<br>
Большее число улучшит качество и увеличит дальность расчёта прорисовки освещённости<br>
Значение по умолчанию: 10</p>
<p><strong>Ограничение дальности расчёта трасселяции</strong><br>
CVar: e_TessellationMaxDistance<br>
Рекомендуется разместить в autoexec.cfg<br>
Расстояние указывается в метрах, где будет прекращен расчёт трасселяции для объектов<br>
Значение по умолчанию: 30</p>
<p><strong>Размер треугольника объекта трасселяции</strong><br>
CVar: r_TessellationTriangleSize<br>
Рекомендуется разместить в autoexec.cfg<br>
Длинна грани треугольника в пикселях для точной трасселяции<br>
Значение по умолчанию: 8</p>
<p><strong>Дальность анимации травы</strong><br>
CVar: e_MergedMeshesInstanceDist<br>
Рекомендуется разместить в autoexec.cfg<br>
Расстояние на котором прекращается анимация травы<br>
Значение по умолчанию: 4,5 (Низкие/Средние/Высокие) 8,0 (Очень Высокие)</p>
<p><strong>Максимальное расстояние прорисовки травы</strong><br>
CVar: e_MergedMeshesViewDistRatio<br>
Рекомендуется разместить в autoexec.cfg<br>
Расстояние на которое прорисовываются интерактивные элементы травы<br>
Значение по умолчанию: 50</p>
<p><strong>Расстояние соотношения LOD (Уровня детализации)</strong><br>
CVar: e_LodRatio<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывает расстояние падения детализации объектов. Большее число означает большее расстояние детальной прорисовки объектов.<br>
Значение по умолчанию: 4 (Низкие), 6 (Средние), 20 (Высокие), 40 (Очень Высокие)</p>
<p><strong>Дистанция видимость (Общее)</strong><br>
CVar: e_ViewDistRatio<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывается значение расстояния на котором будет прекращаться прорисовка объектов<br>
Значение по умолчанию: 25 (Низкие), 35 (Средние), 100 (Высокие/Очень Высокие)</p>
<p><strong>Дистанция видимость (Растительность)</strong><br>
CVar: e_ViewDistRatioVegetation<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывается значение расстояния на котором будет прекращаться прорисовка растительности<br>
Значение по умолчанию: 21 (Низкие), 31 (Средние), 100 (Высокие/Очень Высокие)</p>
<p><strong>Дистанция видимость (Детали)</strong><br>
CVar: e_ViewDistRatioDetail<br>
Рекомендуется разместить в autoexec.cfg<br>
Указывается значение расстояния на котором будет прекращаться прорисовка объектов помеченных как «Детали»<br>
Значение по умолчанию: 19 (Низкие), 24 (Средние), 100 (Высокие/Очень Высокие)</p>
<h5>Тонкая настройка прочих элементов в Crysis 3</h5>
<p><strong>Пропустить видео заставку в Crysis 3</strong><br>
CVar: g_skipIntro<br>
Рекомендуется разместить в system.cfg<br>
Пропустить видео заставку играющую при загрузке игры перед появлением главного меню<br>
Значение по умолчанию: off</p>
<p><strong>Полноэкранный режим окна</strong><br>
CVar: r_FullscreenWindow<br>
Рекомендуется разместить в system.cfg<br>
Когда эта функция активирована, в меню «полноэкранный» режим будет использовать окно, которое заполняет весь экран, что позволяет легко переключаться по Alt-Tab.<br>
Оконный режим будет вести себя нормально<br>
Значение по умолчанию: off</p>
<p><strong>Запретить отображение предупреждений в полноэкранном режиме</strong><br>
CVar: r_FullscreenPreemption<br>
Рекомендуется разместить в system.cfg<br>
Когда опция включена, это предотвращает перехват фокуса всплывающими окнами от мессендеров или системных сообщений.<br>
Значение по умолчанию: on</p>
<p><strong>Принудительный вывод на определённый монитор</strong><br>
CVar: r_overrideDXGIOutput<br>
Рекомендуется разместить в system.cfg<br>
Указывается номер монитор на который будет осуществляться вывод изображения игры. ( — основной, и 1, 2 и т. д. дополнительные мониторы (например телевизор или проектор)<br>
Значение по умолчанию: 0</p>
<p><strong>Поддержка нескольких GPU</strong><br>
CVar: r_MGPU<br>
Рекомендуется разместить в system.cfg<br>
Определяет поддержку нескольких GPU<br>
Значение по умолчанию: Autodetect<br>
Disabled: Отключена поддержка нескольких GPU<br>
Forced: Принудительная поддержка нескольких GPU<br>
Autodetect: CryEngine автоматические определяет включать или нет поддержку нескольких GPU</p>
<p><strong>Аппаратный уровень гамма-коррекции</strong><br>
CVar: r_Gamma<br>
Рекомендуется разместить в system.cfg<br>
Указывается значение аппаратной гамма-коррекции. Оказывает влияние и на рабочий стол.<br>
Значение по умолчанию: 1</p>
<p><strong>Выбраковка окклюзий</strong><br>
CVar: e_CoverageBufferReproj<br>
Рекомендуется разместить в autoexec.cfg<br>
Управление внутренней выбраковкой окклюзий. Не изменяйте значение этой переменной, но если у вас возникнут проблемы при быстром перемещении, то стоит поэксперементировать.<br>
Значение по умолчанию: on</p>
<p><strong>Сетевой порт игры</strong><br>
CVar: g_blaze_gamePort<br>
Рекомендуется разместить в system.cfg<br>
Порт для подключения сетевой игры</p>
<p><strong>Включение Blaze VOIP</strong><br>
CVar: net_blaze_voip_enable<br>
Рекомендуется разместить в system.cfg<br>
Включает и выключает Blaze VOIP<br>
Значение по умолчанию: on</p>
<p><strong>Включение Blaze VOIP PTT</strong><br>
CVar: net_blaze_voip_enable_ptt<br>
Рекомендуется разместить в system.cfg<br>
Включает или выключает Blaze VOIP Push-to-talk<br>
Значение по умолчанию: on</p>
<p><strong>Громкость Blaze VOIP</strong><br>
CVar: net_blaze_voip_playback_volume<br>
Рекомендуется разместить в system.cfg<br>
Регулирует громкость воспроизведения Blaze VOIP в диапазоне от 1,0 до 0,0<br>
Значение по умолчанию: 1,0 (Максимальная громкость)</p>
</div>
