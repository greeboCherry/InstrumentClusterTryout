# InstrumentClusterTryout

Goal of the project is to recreate visually provided design of Instrument Cluster

All input is handled in level blueprint.

## Top part: Controls BP name: Controls.
Only two leftmost controls are plugged into keyboard

Keys: Q and W turns them on, A and S turns them off, Z and X turns them into blinking mode.

Blinking is synchronized among all controls.

## Right part: Media Player (BP name: MediaPlayer)
Arrow keys left and right triggers rotation of presented album covers.

Mashing N rotations queues N rotations up.

Pressing key to rotate in opposite direction zeroes the queue.
