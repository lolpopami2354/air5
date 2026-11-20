CLEARSKY AIRPORT — NEW SURROUNDINGS, REMADE COMPLETE GAME

START
Extract this ZIP into a NEW folder. Open ClearSky-Airport/index.html. The home screen says NEW SURROUNDINGS / REMADE COMPLETE GAME. This is a standalone rebuilt game package, not an updater and not a byte-for-byte recovery of an earlier attachment. Ordinary mouse play does not require Python, external graphics libraries or internet.

NEW ENVIRONMENTS
Old outdoor meshes are replaced. The playable tower interior is retained. New curved segmented terminal/glass facade/canopies, entrances/signs/crossings, covered bus depot with numbered bays/office/equipment, service road markings, aircraft stand guidance/cones/service equipment, jet bridges or stairs, landside roads/parking/cars, cargo/hangars, perimeter fencing, tower shaft, lamp fixtures and terrain/skyline.
Desert: sandstone-colored curved terminal and rocky hills. Metro: taller glass hub, elevated road, parking structures and city skyline. Regional: smaller terminal, trees/green terrain and compact stand positions. Bus starts at the NEW depot (-1740,-370), not the old apron spawn. Preview PNG is actual renderer screenshots with menus hidden for comparison.

ROLES / STAFFING
Playable: Tower Controller, Ground Controller, Bus Driver. Every other job can be NPC or Unstaffed. Ramp/Pushback remain NPC-only roles, not new player gameplay. BUS DRIVER + NPC AIRPORT sets Tower, Ground, Ramp and Pushback to NPC, with Bus Player. Tower and Ground NPCs operate independently/concurrently. Unstaffed jobs do not act and can intentionally stall flights.

BUS / CONNECTED FLIGHT
E enter/exit when stopped. W/S accelerate/brake/reverse. A/D steer. Space brake. F doors/passengers. V cab/exterior. B rear cabin. L lamps. Mouse drag looks/orbits. Touch buttons included.
Collect 24 passengers from terminal pickup (-800,-310), linked to an actual parked flight. Stop within 18 m and F boards (4 simulation seconds). F again closes doors. Drive to the assigned stand, stop within 18 m, F unloads (6 seconds). F closes doors. Clear the AIRCRAFT by more than 60 m. Ramp service, Ground approval and an NPC tug are required before pushback. Ground taxis and hands off; Tower handles takeoff. Further assignments appear as delivered aircraft taxi out. Connected departures award a bonus.

The bus has a world-space 3D interior, dashboard/console, steering wheel, seats, aisle, rails and glazing. Passenger groups are stylized proxies, not 24 independent pathfinding people. Door interlock and basic aircraft-proximity/service-boundary safety stops affect the player bus. Not full collision physics or autonomous obstacle avoidance. NPC bus service is available in other player roles but uses simplified routes. Mirrors are decorative, not live reflections.

GROUND / TOWER
Ground starts in its separate ground-level office with two actual 3D monitors: surface radar excludes airborne targets; operations/radio handles strips, route preview, pushback/taxi/hold/resume/crossings/handoff. Click a monitor to highlight, then click its controls. 2 focuses radar, 3 operations, 1 windows. WASD moves, R resets, mouse wheel zooms. Dashed gold route is preview only; green is issued route.
Tower controls air traffic, active-runway entry, takeoff/landing. Ground controls taxi/pushback. Departures transfer at holding point; arrivals after vacating. Wrong-role instructions are rejected. Runway crossings require Ground request, Tower approval/reservation, then Ground clearance; completion releases reservation. Coordination handles requests; Status shows aircraft controller, phase, wait reason, route points and passenger requirement. This is simplified game logic, not a safe operational ATC model.

RADIO / HEAD CAMERA
Hold Space or radio/microphone buttons; Type is the fallback if browser speech support/permission is unavailable. Ground has a clickable desk mic.
Webcam: enable, allow camera, then Center/C after face detection. Works in Tower, Ground and bus cab. Rotation tracks yaw/pitch; side/forward lean is estimated from one camera and clamped. Enable the respective lean controls. Not full VR tracking. Mouse-look works without a webcam. Camera permission is not requested automatically. Camera and microphone are separate permissions.
For local-file permission restrictions use included Python 3 launchers, then http://localhost:8000. Webcam library/model downloads need internet. Real webcam/model loading, permissions, tracking quality and microphone input were not tested here.

SAVING / SCOPE
Home preferences save locally where supported. Shifts do not save. Home ends the shift after confirmation; Reset view restores a safe starting position. Unexpected JavaScript errors display a recovery notice.
Stylized procedural low-poly scenery, not photorealistic materials. Lamp glow is a simple visual effect, not physically projected lighting/shadows. No multiplayer, fully realistic NPC navigation, complete collision physics, live mirrors, playable ramp/pushback roles or operational guarantees. Fictional layouts/procedures. NOT FOR REAL AVIATION OPERATIONS OR TRAINING.

VALIDATION
Passed JavaScript syntax and ZIP integrity checks. Headless Chromium checks: all three different environments rendered, all three player role starts, correct ground office with two monitors and surface-only target filtering, Ground takeoff rejection, and scripted connected boarding/delivery/safety clearance/NPC pushback/taxi/handoff/departure with next assignment. No uncaught JavaScript errors in those checks. Tests positioned the bus at bays and advanced time programmatically; not exhaustive manual driving, performance, hardware or browser testing.
