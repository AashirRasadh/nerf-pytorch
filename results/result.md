## 🎯 NeRF Training Results (Custom Reduced Iterations)

Due to GPU and time limitations, we trained a reduced version of the NeRF model by manually adjusting the iteration count and sample settings.  
Below are our observed results for different configurations.

---

### 🧩 Iteration: 1,000  
**Sampling:** Coarse only  
**PSNR:** 22.0  

**Result Video:**  
[▶️ Watch Output (Iteration 1K)](file:///D:/Cursor%20Document/nerf-pytorch/results/it10k/WhatsApp%20Video%202025-10-20%20at%2001.23.09.mp4)

---

### 🧩 Iteration: 5,000  
**Sampling:** Coarse + Fine  
**PSNR:** 23.1  

**Result Video:**  
<video src="results/it10k/output2.mp4" controls width="600"></video>

---

### 🧩 Iteration: 25,000  
**Sampling:** Coarse + Fine  
**PSNR:** 25.9  

**Result Video:**  
[▶️ Watch Output (Iteration 25K)](file:///D:/Cursor%20Document/nerf-pytorch/results/it25k/blender_paper_lego_spiral_025000_rgb.mp4)

---

### 🧠 Summary
| Iteration | Sampling Type      | PSNR  | Output Video |
|------------|--------------------|-------|---------------|
| 1,000      | Coarse only        | 22.0  | [View](file:///D:/Cursor%20Document/nerf-pytorch/results/it10k/WhatsApp%20Video%202025-10-20%20at%2001.23.09.mp4) |
| 5,000      | Coarse + Fine      | 23.1  | [View](file:///D:/Cursor%20Document/nerf-pytorch/results/it10k/WhatsApp%20Video%202025-10-20%20at%2001.23.09.mp4) |
| 25,000     | Coarse + Fine      | 25.9  | [View](file:///D:/Cursor%20Document/nerf-pytorch/results/it25k/blender_paper_lego_spiral_025000_rgb.mp4) |

---

💡 *Note:*  
Local file links (starting with `file:///`) will only open if this Markdown file is viewed on your own computer with access to those directories.
