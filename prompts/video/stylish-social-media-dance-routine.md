# Stylish Social-Media Dance Routine (Image-to-Video)

> High-energy, photorealistic social media dance choreography optimized for AI video generators (Kling AI, Runway Gen-3, Luma Dream Machine, Hailuo Minimax, Pika).

---

## 📋 The Prompt

```text
Use the uploaded image as the exact visual reference. The woman performs a stylish, energetic and smooth social-media dance routine in the same studio, wearing the same black outfit. She starts with graceful hand movements, then transitions into coordinated side steps, gentle turns, rhythmic arm movements and confident dance poses, perfectly synchronized to an upbeat pop beat. Keep her face, hairstyle, outfit, body proportions, studio background and overall appearance consistent with the reference image. The camera smoothly follows her movements with subtle cinematic tracking, occasional gentle zoom-in and zoom-out, while keeping her centered in the frame. Natural hair and clothing movement, realistic footwork, smooth transitions, expressive but natural performance. Vertical 9:16, TikTok/Reels style, high-energy choreography, photorealistic, cinematic studio lighting, sharp details, smooth motion, 4K quality, stable camera, no flickering, no body distortion, no extra people, no changes to the background or outfit.
```

---

## ⚙️ Recommended Parameters & Settings

| Parameter | Recommended Value |
| :--- | :--- |
| **Generation Mode** | Image-to-Video (I2V) |
| **Aspect Ratio** | `9:16` (Vertical / TikTok / Instagram Reels / YouTube Shorts) |
| **Resolution** | `1080p` or `4K` (High Quality / Pro Mode) |
| **Framerate** | `24fps` / `30fps` with motion interpolation |
| **Camera Movement** | Cinematic tracking, centered subject, subtle zoom in/out |
| **Duration** | 5s - 10s |

---

## 🔍 Prompt Architecture Breakdown

1. **Reference Grounding**:
   - Explicitly instructs the AI to lock character identity: *"Use the uploaded image as the exact visual reference... Keep her face, hairstyle, outfit, body proportions, studio background and overall appearance consistent with the reference image."*
2. **Action & Choreography Flow**:
   - Defines chronological movement: Hand movements → side steps → gentle turns → rhythmic arm movements → final confident dance pose.
3. **Camera & Cinematography**:
   - Centered subject tracking with cinematic push/pull zooms to replicate professional smartphone/gimbal videography.
4. **Physical Realism & Fluidity**:
   - Natural secondary dynamics (hair physics, clothing movement, grounded footwork).
5. **Negative Constraints & Defect Suppression**:
   - Embedded negative constraints prevent common AI video artifacts: *"stable camera, no flickering, no body distortion, no extra people, no changes to the background or outfit."*

---

## 🚀 Model-Specific Tips

- **Kling AI (v1.5 / Pro)**:
  - Upload the source frame in **Image-to-Video**.
  - Set Creativity / Relevance Slider to **0.65 - 0.75** to maintain face consistency while allowing energetic dance movement.
  - Optional: Use Camera Movement controls (Zoom In / Track) or Motion Brush on the arms/legs.
- **Runway Gen-3 Alpha**:
  - Add motion slider: `5` to `7` for dynamic dancing without limb deformation.
- **Hailuo AI (Minimax Video-01)**:
  - Strong adherence to character consistency and realistic physics; works great with the prompt verbatim.
- **Luma Dream Machine**:
  - Pair with Camera Motion prompt options for enhanced tracking smoothness.
