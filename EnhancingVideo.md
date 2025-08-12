
#  **5. Editing Workflow – Step-by-Step in OpenShot**

This section covers the basic editing operations you'll use most often while working on a video project.

---

##  **A. Add Videos to Timeline**

1. Import your video using **Import Files** or drag it into the **Project Files** panel.

    <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/importfile-1.png" style="width: 500px;">
2. Drag the video from **Project Files** into a **track on the Timeline** (e.g., Track 1).

    <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/drag-01.png" style="width: 500px;">
3. You can layer multiple videos on different tracks if needed.

---

##  **B. Trim or Clip a Video**

### Method 1: **Trim by dragging**

* Hover over the **start or end  [↔]** of a video clip.

   <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/trim-01.png" style="width: 500px;">
* Click and **drag inward** to shorten the clip (trim the edges).

   <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/trim-02.png" style="width: 500px;">
    <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/trim-03.png" style="width: 500px;">

### Method 2: **Clip using Razor Tool**

* Select the **Razor Tool** (scissors icon) from the toolbar.

 <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/trim-scissors-04.png" style="width: 500px;">
  * Click on the video clip at the point where you want to **split** it.

   <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/trim-03.png" style="width: 500px;">

* You can delete or move each segment individually.

---

##  **C. Reposition Clips**

* Click and **drag any clip** along the timeline to move it.
* You can **drag clips between tracks** (e.g., move from Track 2 to Track 1).

  <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/reposition-01.png" style="width: 500px;">

---

##  **D. Adjust Clip Length**

* Hover over either edge of a clip.
* Drag left or right to **shorten** or **extend** the duration of that clip on the timeline.

   <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/shortenorextend-1.png" style="width: 500px;">


---

##  **E. Add Effects to Clips**

1. Go to `View > Views > Effects` or use the **Effects tab [1]**.

 <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/effects-1.png" style="width: 500px;">

2. Drag an effect (e.g., **Blur**, **Brightness**, **Chroma Key [2]**) onto a video or image clip.

 <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/effects-2.png" style="width: 500px;">

3. **Right-click the clip [3] [4]** > **Properties [5]** to tweak the effect parameters.

 <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/effects-3.png" style="width: 500px;">

4. To remove an effect, **right-click [6]** > Remove Effect **[7]**.

   <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/effect-4.png" style="width: 500px;">

---

##  **F. How to Add Subtitles (Captions) in OpenShot**

### Step 1: Import and Place Your Video

* Open your video project in OpenShot.
* Import your video file if you haven't already, then drag it onto the timeline.
  <img src="https://github.com/LEARN-LK/Openshot/blob/main/img/importfile-1.png" style="width: 500px;">

### Step 2: Apply the Caption Effect

* Open the **Effects** panel (if not visible, enable it via `View > Views > Effects`).
* Locate the **Caption** effect and **drag it onto your video clip** on the timeline.
 
### **Step 3 – Open and Edit the Caption Text (with Accurate Timing)**

1. **Right-click** on the video clip that has the **Caption** effect applied.
2. Select **Edit Caption** (or a similar option depending on your OpenShot version).
3. A **caption editor** will open where you can type in your subtitle or caption text.
4. To create subtitles:

   * Carefully **listen to the video** and note the **start** and **end times** for each line of dialogue or narration.
   * Type the subtitle text for the first line.
5. **Click the “+” icon** in the caption editor to add another **time slot** for the next subtitle.
6. Play the video and identify the **start** and **end time** for the next line of speech.
7. Enter the subtitle text and adjust the start/stop times precisely.
8. Repeat this process for all lines until your video is fully captioned.

---

### **Example: Provided Video Timing & Subtitles**

Here’s an example timecoded subtitle sequence based on the reference video:

```
00:00:10:000 --> 00:00:12:000
This male Arctic Fox

00:00:12:733 --> 00:00:15:000
Has spent the last six months

00:00:17:333 --> 00:00:18:000
Alone

00:00:19:000 --> 00:00:23:066
He really goes the distance

00:00:23:066 --> 00:00:25:633
When food is in short supply

00:00:26:666 --> 00:00:31:066
One even clocked more than a thousand miles

00:00:31:066 --> 00:00:32:733
In just over two months.

00:00:37:733 --> 00:00:39:666
This little guy

00:00:39:666 --> 00:00:42:700
Has been surviving off his street smarts.

00:00:49:700 --> 00:00:53:933
You can't be too careful when you are only 12 inches tall.
```

---
 ** Tips:**

* Keep each subtitle **short and readable** (usually 1–2 lines max).
* Give viewers **at least 1–1.5 seconds** to read each caption.
* Adjust timing so that subtitles appear **just before the speech starts** and disappear **right after it ends**.

---


### Step 4: Customize Font, Size & Color

* Within the Caption editor, adjust:

  * **Font type**
  * **Font size**
  * **Font color**
* These settings will apply to the entire caption block.
  
### Step 5: Adjust Timing for Each Caption

* Set the **start and end times** so that the caption appears at the right moment in your video.
* If you need different style elements (e.g. color, font) for separate lines, add **multiple Caption effects**—each with its own timing and properties.

---

##  Tips 

> “There is a Caption effect in the Effect tab that you can drag and drop on your video clip to add Captions.”

> “If you would like to change the color, font, etc., in different spots in your video, you can add multiple Caption effects to the same clip. You just have to manage the times and content of each Caption separately.”
)

---

### Summary Table

| Step | Action                                                  |
| ---- | ------------------------------------------------------- |
| 1    | Import your video and add it to the timeline.           |
| 2    | Apply the Caption effect from the Effects panel.        |
| 3    | Right-click → Edit Caption and enter your text.         |
| 4    | Customize font, size, and color for the subtitle block. |
| 5    | Set correct timing for appearance on the timeline.      |
| 6    | For stylistic variations, use multiple Caption effects. |

---












---

##  **G. Divide Video into Sections**

1. Use the **Razor Tool** to cut the video into different sections.
2. Each section becomes a separate clip.
3. You can:

   * Move, rearrange, or delete individual sections.
   * Add **transitions** between them (drag from Transitions tab).
   * Apply different effects to each section.

---

##  **H. Add Images to Video**

1. Import images (PNG, JPG) using the **Import Files** button.
2. Drag the image onto the **Timeline**, typically above the video track (e.g., Track 2 or 3).
3. Adjust the image duration by dragging its ends.
4. Use right-click > **Transform** to resize or reposition the image.
5. Optionally, add effects like fade-in/out or animation with keyframes.

---

