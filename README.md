# Fingerprint authentication in flutter

A Fingerprint authentication in flutter Flutter project.

## Getting Started

A fingerprint authentication system in flutter for android application. Nowadays many phones are equipped with a fingerprint sensor which makes login and local authentication easier for the user and more secure than using a password.

## Setting up our project
INitially in the app need to set up a couple of things first.
the first thing that need to do is to add the local_auth dependencies inside our pubspec.yaml file
	local_auth: ^0.4.0+1
	
	
After adding dependency now need to add the user-permission inside the AndroidManifest.xml file(android -> app -> src -> main -> AndroidManifest.xml).
 <uses-permission android:name="android.permission.USE_BIOMETRIC" />
 <uses-feature android:name="android.hardware.fingerprint" android:required="true" />
 
This is for an android phone only, for IOS it's not the same.


