# Meowstic Gestures
Neural network based multitouch gestures recognizer for Linux, written in Rust.

## Concept
Touch events from X11/Wacom/Synaptics/whatever are translated into image, other possibility is to use each finger trace as discrete time-based signal. Adding gestures requires training neural network, recognition is simple. API will provide centroid position, bounding box, number of fingers and recognized gesture.

Project will be used in utility for managing windows in bspwm using touchscreen of some notebooks.

## Availability
Project will be started as soon as I manage to find some spare time (finishing master thesis).
