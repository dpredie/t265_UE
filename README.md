# t265_UE
Intel Realsense t265 into Unreal Engine. Windows only!

Simple script that sends data into Unreal Engine through the JSON liveLink plugin. Can be configured to send to another IP as well.

# Instructions
1. Install the SDK from Intel https://www.intelrealsense.com/sdk-2/
2. Install JSON-Livelink plugin into your project - https://github.com/ue4plugins/JSONLiveLink
3. Configure livelink to recieve on localhost.

![image](https://user-images.githubusercontent.com/23232326/136547962-7b521660-e3d3-4b53-8ab5-6809187c0366.png)

4. Install python, and run tracker.py

5. Add livelink component to your camera

![image](https://user-images.githubusercontent.com/23232326/136548300-f6686048-9b91-4e7f-9efd-17a724fe0d9e.png)

6. choose MHtrack as your "Subject representation"

![image](https://user-images.githubusercontent.com/23232326/136548328-ad5ef274-c035-4902-80c3-da6240c994ec.png)



Thats it! 




