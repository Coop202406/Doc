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

## ChatGPT Generated:
Limited free use

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

$$
Climate \_Normal_{(typeperiod, month)}=\frac{\sum_{i=Startyear}^{Endyear} [\sum_{i=Startymonth}^{End_{month}} (Climate \value_{(typeday, monthyear)})]} {( End_{month}-Start_{month}) \times30} 
$$
