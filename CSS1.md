* px: Always the same size, no matter the screen.

            p {
            font-size: 16px;
            }
            Always 16 pixels, no matter screen size.

* rem: Size changes if the root font size changes (good for scaling).

            html {
            font-size: 16px;
            }
            p {
            font-size: 1.5rem; /* 1.5 × 16 = 24px */
            }
            If root size changes, all rem-based sizes adjust.

* vh: Size changes based on how tall your screen/window is.

            .section {
            height: 100vh;
            }
            Section takes up 100% of the viewport height (full screen).
