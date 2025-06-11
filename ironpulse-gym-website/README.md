# IronPulse Fitness Hub 🏋️‍♂️

A comprehensive fitness website featuring workout routines, meal plans, equipment guides, and fitness tips to help users achieve their health goals.

## Features ✨

- **Responsive Navigation**: Clean menu with hover effects
- **Interactive Components**:
  - Pulsing call-to-action buttons
  - Hover-animated video thumbnails
  - Scrolling news ticker
- **Workout Library**: Detailed exercise table with icons
- **Meal Planning System**: Categorized by goals, food types, and health focus
- **Equipment Guides**: Visual references for home gym setup
- **Fitness Tips**: Curated list of professional advice

## Technologies Used 💻

![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white)
![Flexbox](https://img.shields.io/badge/-Flexbox-7952B3?logo=css3&logoColor=white)
![CSS Animations](https://img.shields.io/badge/-Animations-FF6B6B)

## Key Implementation Details 🛠️

### Advanced CSS Techniques
- **Flexbox Layout**: Responsive item containers with `flex-grow` and `flex-shrink`
- **Hover Effects**: 
  ```css
  .video-item:hover {
    transform: scale(1.2, 1.1);
    background-color: #ebb6b6;
  }
  ```
## Animation System

  - Pulsing buttons with @keyframes pulse

  - Smooth scrolling ticker with transform: translateX
## Semantic Structure
- Proper sectioning with <section> tags

- Accessible table structure for workout data

- Mobile-first approach (with hamburger menu placeholder)

## Clone repository 📦
```bash
git clone https://github.com/bhargavatejagolla/ironpulse-fitness.git
```
## Highlighted Code Snippets 💡
  - Interactive Video Thumbnails:
    ```css
      .video-item:hover::after {
        opacity: 1; /* Play icon appears on hover */
        transition: opacity 0.3s ease;
      }
    ```
  - Responsive Meal Plan System :
      ```css
      .item-container {
      display: flex;
      overflow: hidden;
      }
      .item-second {
        flex-grow: 3; /* Priority item expands more */
      }
    ```
## Future Enhancements 🚀
  - Add JavaScript for dynamic content loading

  - Implement user accounts and progress tracking

  - Create workout video library

  - Add dark mode toggle

  - Develop mobile-responsive navigation
---

## 🙌 Contributing

Contributions are welcome! If you'd like to suggest improvements or new features, feel free to fork the repo and submit a pull request. Let's build a stronger fitness community together. 💪

---

## 📫 Contact

Created with 💖 by [Bhargava Teja Golla](https://github.com/bhargavatejagolla)

For any queries, reach out via [LinkedIn](https://www.linkedin.com/in/golla-bhargava-teja/) or open an issue on this repository.

---

---
## 🔒 License

This project is licensed under the [MIT License](LICENSE).
    

