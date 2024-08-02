## Mathematical Notations on Markdown
This is to see correct editing for '\$' to check $`\sqrt{4}`$ vs $`\sqrt{\$4}`$


Testing more complex notation:
**The Cauchy-Schwarz Inequality**
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$


## From Algorithm document
Equation 1.6.2-1
$$ ET_r = 0.013 * \frac{T_{mean}}{T_{mean +15}} * \left( 23.8856 * R_s + 50\right)  $$

For RH < 50%

$$
ET_r = 0.013 \times \frac{T_{\text{mean}}}{T_{\text{mean}} + 15} \times (23.8856 \times R_s + 50) \times \left(1 + \frac{50 - RH_{\text{mean}}}{70}\right)
$$

# Using Image to generate markdown for formulas

## ChatGPT Generated: For non-tech users/ modfiers

<img src="Screenshot 2024-08-01 135513.png"> Image uploaded</img>
<br>
 <p>Limited free use</p>

For RH >= 50%

$$
ET_r = 0.013 \times \frac{T_{\text{mean}}}{T_{\text{mean} + 15}} \times (23.8856 \times R_s + 50)
\quad \text{Eq. 1.6.2-1}
$$

For RH < 50%

$$
ET_r = 0.013 \times \frac{T_{\text{mean}}}{T_{\text{mean} + 15}} \times (23.8856 \times R_s + 50) \times \left(1 + \frac{50 - RH_{\text{mean}}}{70}\right)
\quad \text{Eq. 1.6.2-2}
$$

$$
K_c = a + b \left(\frac{T_{\text{max}} - T_{\text{min}}}{2} - T_{\text{base}}\right) + c \left(\frac{T_{\text{max}} - T_{\text{min}}}{2} - T_{\text{base}}\right)^2 + d \left(\frac{T_{\text{max}} - T_{\text{min}}}{2} - T_{\text{base}}\right)^3 +
\quad \text{Eq. 1.6.2-3}
$$

For grasses, a non-linear function to calculate \( K_c \) is used.

$$
K_c(\text{grass}) = a \times \left[ 1 - e^{\left(-b \times \left(\frac{T_{\text{max}} - T_{\text{min}}}{2} - T_{\text{base}}\right)\right)}\right]
\quad \text{Eq. 1.6.2-4}
$$

$$
ET_c = K_c \times ET_r
\quad \text{Eq. 1.6.2-5}
$$


## Pix2Text: (Free)
[https://p2t.breezedeus.com/](https://p2t.breezedeus.com/)

<img src = "\Screenshot 2024-08-01 134150.png">Image uploaded</img>


$$
C l i m a t e \_N o r m a l_{( t y p e, p e r i o d, m o n t h )}=\frac{\sum_{i=S t a r t y e a r}^{E n d y e a r} \left[ \sum_{i=S t a r t y e a r t}^{E n d_{m a t h}} ( c l i m a t e \_v a l u e_{( t y p e d a y, m o n t h, y e a r )} ) \right]} {( E n d_{m a t h}-S t a r t_{m a t h} ) \times3 0} 
$$
