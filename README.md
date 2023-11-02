#MAD_Pr-8_21012021087

Aim: What is BroadcastReceiver? Difference between Service and BroadcastReceiver. Create an Alarm application by using service & BroadcastReceiver by following below instructions.

Create MainActivity according to below UI design.

Create AlarmBroadcastReceiver class

Create AlarmService Class

Add android.permission.SCHEDULE_EXACT_ALARM Permission in Manifest file

Ans:-

Broadcast in android is the system-wide events that can occur when the device starts, when a message is received on the device or when incoming calls are received, or when a device goes to airplane mode, etc. Broadcast Receivers are used to respond to these system-wide events. Broadcast Receivers allow us to register for the system and application events, and when that event happens, then the register receivers get notified.

Apps can use services to do long-running processes in the background, such as downloading files from a server, or checking for email, or checking your location. Although services don't show up or interact with you directly, they still show up in the "Running apps" list. Broadcast receivers are the third kind of component. Like services, they only exist in the background and don't interact with you directly. But unlike services, they can't stay running or perform long tasks: they exist to respond to events. And unlike activities and services, more than one broadcast receiver can be started in one go.

Output:

![WhatsApp Image 2023-11-02 at 23 22 14_87d054d2](https://github.com/sujalpatel187/MAD_Pr-8_21012021087/assets/98510141/414302c5-fb51-4eaa-924a-60d773e3c11c)
![WhatsApp Image 2023-11-02 at 23 22 14_639c1dcd](https://github.com/sujalpatel187/MAD_Pr-8_21012021087/assets/98510141/b3dcd115-3a3b-443f-a1c2-23937eeb2e63)
![WhatsApp Image 2023-11-02 at 23 22 15_9e75848f](https://github.com/sujalpatel187/MAD_Pr-8_21012021087/assets/98510141/1d975302-fef8-4bbe-89b7-f43948790c2a)


