# Projects
Hey there! Thanks for dropping by my Github page. Below you'll find a collection of the recent projects I've been working on and have been able to make publicly available. I have a few more in the works but they aren't quite ready to share. Many of these projects have been used in a variety of presentations and webinars for Datadog. Some are just for fun and personal experimentation. 

| Project Name             | Code  | Live Demo | Description                                                                                                                                                                                                                   |
|--------------------------|-------|-----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Generative Debrief**       | [Code](https://github.com/jasonhand/generative-debrief)     | -         | An app written to demonstrate using OpenAI with Azure Logic Apps and Datadog for a webinar taking place on May 14th, 2024.                                                                                                     |
| **Doggo Explorer**           | [Code](https://github.com/jasonhand/doggo-explorer)     | [Live Demo](https://jasonhand.github.io/doggo-explorer/)         | An app written to demonstrate using Datadog's Real User Monitoring (RUM) as part of an on-stage demo during my presentation at Google Cloud Next '24.                                                                         |
| **Video Tools (20 in total)**              | [Code](https://github.com/jasonhand/video_tools)     | -         | A command line app written to assist in video, audio, and transcription needs I've had while working on various projects at Datadog.                                                                                          |
| **Vinyl Viewer**             | [Code](https://github.com/jasonhand/vinyl-viewer)     | [Live Demo](https://jasonhand.github.io/vinyl-viewer/)         | An app written to visualize my vinyl record collection including Spotify integrations to listen to clips from the record.                                                                                                     |
| **Ignite Karaoke**           | [Code](https://github.com/jasonhand/js-ignite-karaoke)     | [Live Demo](https://jasonhand.github.io/js-ignite-karaoke/)         | An app written to play "Ignite Karaoke" with the Datadog Advocacy team during one of our off-site meetings.                                                                                                                   |
| **PsPsPs**                   | [Code](https://github.com/jasonhand/pspsps)     | -         | An app written to view cats and dogs while I searched for a new kitten. It uses the Petfinder API.                                                                                                                           |
| **Generative AI Notebooks**  | [Code](https://github.com/jasonhand/notebooks)     | -         | A collection of Jupyter (or Google Collaboratory) notebooks to demonstrate various generative AI use cases using a variety of Google's Large Language Models used in a webinar with Google.                                   |
| **Spotify Dogged**           | [Code](https://github.com/jasonhand/spotify_dogged)     | -         | A command line app written to retrieve listening data from Spotify to create your own personal "Spotify Wrapped", while demonstrating how to send custom logs to Datadog.                                                     |
| **Mandolin Classifieds**      | [Code](https://github.com/jasonhand/mandolin-classifieds)     | [Live Demo](https://jasonhand.github.io/mandolin-classifieds/)         | An app written to browse mandolin classified ads from Mandolin Cafe in a more visual appealing way while also randomizing the order in which they are displayed.                                                              |
| **Command Line ChatGPT**     | [Code](https://github.com/jasonhand/cli-gpt-python-chatbot)     | -         | A command line app written to communicate with OpenAI's ChatGPT.                                                                                                                                                              |
| **Video Splitter**           | [Code](https://github.com/jasonhand/VideoSplitter)     | -         | A command line app written to automatically create short-form videos in portrait orientation from random spots in a longer video for use as YouTube Shorts, TikToks, Instagram Stories, etc. This was added to "Video Tools". |
| **YNAB Balances**            | [Code](https://github.com/jasonhand/ynab_balances_to_csv)     | -         | A command line app to download "You Need A Budget" transactions to a CSV for local processing.                                                                                                                                 |


## Generative Debrief

![](https://github.com/jasonhand/generative-debrief/raw/main/images/screenshot.png)

## Doggo Explorer

![](https://github.com/jasonhand/doggo-explorer/raw/main/images/doggo-explorer_thumb.png)

## Video Tools (20 in total)

![](https://github.com/jasonhand/video_tools/raw/main/tutorial/tutorial1_thumb.png)

### Tool descriptions

1. **🚀 [2xSpeed - Video Speed Doubling](https://github.com/jasonhand/video_tools/blob/main/services/2xSpeed/2xSpeed_README.md)**: Accelerates the playback speed of video files, perfect for creating time-lapse effects or shortening content duration.

2. **🎵 [Apple Audio to MP3 Converter](https://github.com/jasonhand/video_tools/blob/main/services/apple-to-mp3/convert_m4a_to_mp3_README.md)**: converts M4A audio files to MP3 format using FFmpeg.

3. **🔲 [Black_bars - Black Bar Removal](https://github.com/jasonhand/video_tools/blob/main/blob/main/services/black_bars/black_bars_README.md)**: Efficiently removes black bars from videos, resizing and cropping to fit a specified resolution.

4. **🖼️ [Burn Logo - Logo Overlay Utility](https://github.com/jasonhand/video_tools/blob/main/services/burn_logo/burn_logo_README.md)**: Adds logos or watermarks to videos by overlaying images, with customizable positioning and sizing.

5. **🔤 [Captions - Burning Captions into Video](https://github.com/jasonhand/video_tools/blob/main/services/captions/captions_README.md)**: Burns subtitles from SRT files into videos, positioning them for better visibility and accessibility.

6. **📄 [Chunk](https://github.com/jasonhand/video_tools/blob/main/services/chunk/chunk_README.md)**: chunks a large text file into smaller sections, each with a specified maximum number of tokens, and saves the output as a new text file.

7. **✂️ [Clip - Video Trimming and Enhancement](https://github.com/jasonhand/video_tools/blob/main/services/clip/clip_README.md)**: Trims the start of videos and enhances their quality, ideal for removing unwanted sections and improving overall presentation.

8. **[Crop - Crop videos segments](https://github.com/jasonhand/video_tools/blob/main/services/clip/clip_README.md)**: automates the process of cropping videos to a portrait orientation, focusing on the center of the video.

9. **🔍 [Key Words](https://github.com/jasonhand/video_tools/blob/main/services/key_words/key_words_README.md)**: Analyze a text file, filtering out common "stop words" and additional uninteresting words to identify and count the most meaningful words.

10. **🎨 [Make-gif - GIF Conversion Utility](https://github.com/jasonhand/video_tools/blob/main/services/make_gif/make_gif_README.md)**: Converts videos into high-quality GIFs, using a custom color palette to maintain visual fidelity.

11. **[Montage - Concactenate Multiple Videos](https://github.com/jasonhand/video_tools/blob/main/services/montage/montage_README.md)**: Create a video montage by clipping random sections from each video in a specified directory and merging them into a new video of a predetermined length. 

12. **[.Mov to .Mp4 Converter](https://github.com/jasonhand/video_tools/blob/main/services/Mov_to_Mp4/mov_to_mp4_README.md)**: converts video files from `.MOV` format to `.MP4` format, maintaining the original file's name but changing its extension.

13. **🎵 [Mp3 - Video to MP3 Conversion Utility](https://github.com/jasonhand/video_tools/blob/main/services/mp3/mp3_README.md)**: Extracts audio from video files and saves it as high-quality MP3 files, useful for isolating audio tracks or creating transcripts.

14. **🎞 [Shorten - Video Clipping Utility](https://github.com/jasonhand/video_tools/blob/main/services/shorten/shorten_README.md)**: Creates new videos from selected portions of existing ones, facilitating the creation of highlight reels or content summaries.

15. **📌 [Splitter - Video Clip Processor](https://github.com/jasonhand/video_tools/blob/main/services/splitter/splitter_README.md)**: Generates multiple clips from a single video, adding consistent graphical overlays to each snippet.

16. **🖼 [Stacked - Portrait Stacked](https://github.com/jasonhand/video_tools/blob/main/services/stacked/stacked_README.md)**: Combines speaker footage and slide content into a single portrait video, enhancing video presentations.

17. **📝 [Transcribe SRT - Generates (SRT) Transcription from Mp3](https://github.com/jasonhand/video_tools/blob/main/services/transcribe/transcribeSRT_README.md)**: Transcribes audio into written text with timestamps using OpenAI's Whisper model, ideal for generating accurate subtitles.

18. **📝 [Transcribe TXT - Generates (TXT) Transcription from Mp3](https://github.com/jasonhand/video_tools/blob/main/services/transcribe/transcribeTXT_README.md)**: Transcribes audio into written text with timestamps using OpenAI's Whisper model, ideal for generating accurate subtitles.

19. **🔪 [Trimmer - Video Trimming Utility](https://github.com/jasonhand/video_tools/blob/main/services/trimmer/trimmer_README.md)**: Offers a straightforward method for trimming videos to a specific duration without re-encoding, preserving the original quality.

20. **🆙 [Upscale - Video Upscaling Utility](https://github.com/jasonhand/video_tools/blob/main/services/upscale/upscale_README.md)**: Upscales videos to higher resolutions, incorporating optimal settings for enhanced video and audio quality.

## Vinyl Viewer

![](https://github.com/jasonhand/vinyl-viewer/raw/main/images/vinyl-viewer2_thumb.png)

## Ignite Karaoke

![](https://github.com/jasonhand/js-ignite-karaoke/raw/main/img/Ignite_Karaoke_thumb.png)

## PsPsPs

![](https://github.com/jasonhand/pspsps/raw/main/images/PsPsPs_thumb.png)

>NOTE: Requires the [PsPsPs Proxy Project](https://github.com/jasonhand/psps-proxy)

## Generative AI Notebooks

![](https://github.com/jasonhand/notebooks/blob/main/images/screenshot_thumbnail1.png)

**Notebooks:** 

- [Grocery Store Receipt Analysis](https://github.com/jasonhand/notebooks/blob/main/grocery-receipt-analysis.ipynb)
- [NASA Short Story](https://github.com/jasonhand/notebooks/blob/main/nasa-short-stories.ipynb)
- [Market Summary](https://github.com/jasonhand/notebooks/blob/main/market-summary.ipynb)
- [Restaurant Reviews](https://github.com/jasonhand/notebooks/blob/main/restaurant-reviews.ipynb)
- [Datadog Custom Logs & Metrics](https://github.com/jasonhand/notebooks/blob/main/datadog-custom-logs.ipynb)

## Spotify Dogged

![](https://github.com/jasonhand/spotify_dogged/raw/main/img/screenshot_2_thumb.png)

## Mandolin Classifieds

![Mandolin Classifieds](https://github.com/jasonhand/mandolin-classifieds/raw/main/images/screenshot_thumb.png)

## Command Line ChatGPT Interface

![CLI-GPT](https://github.com/jasonhand/cli-gpt-python-chatbot/raw/main/images/screenshot-terminal_thumb.png)

## Video Splitter

![Video Splitter](https://github.com/jasonhand/VideoSplitter/raw/master/documentation/clipped_video_thumb.png)

>NOTE: This has been integrated into the [Video Tools Project](https://github.com/jasonhand/video_tools)




