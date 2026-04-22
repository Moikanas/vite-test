# OBS (Open Broadcaster Software) setup as instant replay replacement guide

1. Download and install OBS : <https://obsproject.com/download>
2. Setup first launch : Choose Optimize just for recording

   ![obs_guide12.png](.attachments.20806/obs_guide12.png)
3. Choose your preference for fps 

   ![obs_guide11.png](.attachments.20806/obs_guide11.png)
   1. Review and apply settings

      ![obs_guide6 (2).png](.attachments.20806/obs_guide6%20%282%29.png)

# Replay Buffer setup

1. Open Output settings :

   ![obs_guide7 (2).png](.attachments.20806/obs_guide7%20%282%29.png)
   1. Select Output Mode : Simple

      Set Video Bitrate value of your preference 

      ### [Youtube Recommended Bitrate chart](https://support.google.com/youtube/answer/1722171?hl=en#zippy=%2Cbitrate)

      | Type       | Video Bitrate, Standard Frame Rate  
      (24, 25, 30)      | Video Bitrate, High Frame Rate  
      (48, 50, 60)      |
      |------------|------------------------------------------------------|--------------------------------------------------|
      | 8K         | 80 - 160 Mbps                                        | 120 to 240 Mbps                                  |
      | 2160p (4K) | 35–45 Mbps                                           | 53–68 Mbps                                       |
      | 1440p (2K) | 16 Mbps                                              | 24 Mbps                                          |
      | 1080p      | 8 Mbps                                               | 12 Mbps                                          |
      | 720p       | 5 Mbps                                               | 7.5 Mbps                                         |
      | 480p       | 2.5 Mbps                                             | 4 Mbps                                           |
      | 360p       | 1 Mbps                                               | 1.5 Mbps                                         |

      Set the rest for your preferences

      ::: info
      Make sure you have enabled Replay buffer,set Maximum Replay time and hit apply.

      :::

![obs_guide13.png](.attachments.20806/obs_guide13.png)

1.  Set hotkey for Save replay 

   ::: warn
   Make sure to hit apply after step 6 otherwise you will not be able to see an option for Save Replay hotkey

   :::

   ![obs_guide8.png](.attachments.20806/obs_guide8.png)
2. Add a Display,Game or Window capture and start Replay Buffer

   ![obs_guide9.png](.attachments.20806/obs_guide9.png)

## Auto startup with windows guide (optional)

1. Find the path of your obs installation and create a shortcut for the obs64 file

   ![obs_guide3.png](.attachments.20806/obs_guide3.png)
2. Right click on the shortcut and select Properties

![obs_guide14.png](.attachments.20806/obs_guide14.png)

1. Add *--startreplaybuffer* on the end of the target path and click apply/ok

   ![obs_guide4 (2).png](.attachments.20806/obs_guide4%20%282%29.png)
2. Open run (win+r) and write *shell:startup*

   ![obs_guide2.png](.attachments.20806/obs_guide2.png)
3. Move the shortcut on that folder

   ![obs_guide1.png](.attachments.20806/obs_guide1.png)

::: success
Done!

:::