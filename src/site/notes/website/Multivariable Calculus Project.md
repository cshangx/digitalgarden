---
{"dg-publish":true,"permalink":"/website/multivariable-calculus-project/","created":"2025-02-18T13:56:32.790+08:00","updated":"2025-02-26T22:06:29.141+08:00"}
---

________
---


## Chuning Shang
## Project 3 Chapter 14
### Hyperthermia Treatments for Tumors 
#### February 26, 2025


### Part 1: Different shapes and types of tumors, Types of Cancer treatments, and their Effectiveness (500 words)

Tumors are like *humans* - they can come in many different personalities, shapes, and sizes. Some might be reckless and dangerous, while others might be milder and less aggressive. Tumors, in particular, come in all sorts of shapes; some of these shapes may imply "personalities". For instance, rounder tumors are usually the nice and behaving, harmless tumors. The tumors that might be multi-lobed and "bumpy" can have personalities that might insinuate a mixture of both; potentially harmful, potentially harmless, and unverifiable unless you take a closer look to get to know them better, as are the tumors that take on a finger-like shape. However, beware when you see tumors with jagged and spiky edges or ulcerated tumors with crater shapes! These are bound to be trouble. However, we should not always judge a book by its cover, or in this case, a tumor by its curves and spikes. To make sure that you're judging the harmfulness of these tumors, we have to classify them even further and run tests to ensure accuracy. 

![Pasted image 20250226214742.png|200](/img/user/Pasted%20image%2020250226214742.png)

There are many different ways to categorize tumors, such as classification by tissue type, behavior, as well as location in the body. However, classifying tumor type by its tissue origin is generally the most common. For instance, tumors growing in the epithelial tissue are carcinomas, while tumors in the connective tissue are sarcomas, tumors inside the brain are gliomas, and tumors in blood-forming tissues are leukemia. The other two classification methods, **behavior** (determining if a tumor is malignant, or benign), and **location** are used to determine which treatment method would be the most effective.

Then, in order to eliminate the pesky little unobeying tumor-kid delinquents, we can further group cancer treatments into two major treatments depending on the area that the treatment affects.

First, **Local Treatments** focus on specific areas of the body that need tumor treatments. Many of these local treatments can be combined with **Systemic treatments**, like Chemotherapy, that increase the chance of success. 

>[!info] **Surgery** is the most viable and widespread option since it removes the malignant tumor entirely, making it unlikely to reoccur. It is primarily used to remove local tumors. Laser Therapy also works in similar ways to precisely cut off or vaporize malignant tumors.

>[!info] **Radiation Therapy** targets localized areas that are located in places extremely hard to remove, such as the brain. This method shrinks tumors so that it would be easier to operate on before surgery, and is also used after surgery to remove any excess. 

>[!info] **Cryotherapy**, also known as **Cryoablation**, is also a great method for people who are unable to proceed with surgical methods of removal due to other complications, such as heart disease. This is a non-invasive method that essentially targets localized tumors located usually in the liver, prostate, or kidneys, and freezes these tumors without damaging the surrounding tissue cells. A huge advantage of this as compared to other methods like surgery is its quick and friendly recovery time and far fewer complications. 

At the opposite end of the spectrum, are treatments that are applied using heat. The first type is
>[!info] **radiofrequency ablation**, which uses heat from 50 to 100 degrees Celsius introduced into the tumor using a needle probe. 

This treatment is typically used for small tumors less than 5 centimeters in diameter, and effectively destroys the tumor cells. On the other hand, 
>[!info] ** Hyperthermia** is applied to tumor cells that are recurrent and soft tissue sarcomas using external heat applications such as microwaves to around 40 to 50 degrees Celsius, allowing larger tumor areas to be treated and then used alongside another treatment method for easier cancer elimination.

For skin cancer, 
>[!info] **topical treatments** are applied to target the cancerous skin cells on the skin's surface.

**Systemic Treatments** are treatments that are effective in targeting all cancer areas throughout the entire body. The most common type of systemic treatment is chemotherapy, which kills off all cells that divide too fast. While it is effective in treating many forms of cancer like breast cancer or leukemia, a side effect of chemotherapy is that it leaves the patient extremely fatigued and induces hair loss. Immunotherapy helps the body to block the proteins inside our body that prevent the immune system cells from attacking cancer cells or introduces proteins that help fight cancer cells like immune system cells. Similarly, Targeted Therapy also introduces antibodies and inhibitors that can prevent cancer cells from operating. 

In addition, for cancer that affects the reproductive system, like breast cancer and prostate cancer, a common treatment is hormone therapy, which helps to lower specific hormones that induce cancerous cell behavior.

For cancers like leukemia that affect bones, another viable way to treat is to replace the harmful bone marrow with either the patient's own stem cells, or to get donated healthy stem cells to inject back in. 



![Pasted image 20250226214953.png|350](/img/user/Pasted%20image%2020250226214953.png)






---------------------

## Part 2


### I. A Necessary Measurement?

It is not necessary to measure the temperature of the tumor's center once we have verified that the temperature at half the radius of the tumor has already reached the effective temperature. Since it is given that the temperature gets hotter closer to the center, we can assume that the tumor's center is already hotter than the effective temperature, since the temperature at half the radius has indeed reached the effective temperature. 









---------------------

### II. Treating a Spherical Tumor

The volume of a sphere is as follows:
$$
V=\frac{4}{3}r^3.
$$
$$
\frac{1}{4}r: V_{T} = \frac{4}{3}(\frac{1}{4}r)^3 = \frac{1}{48}r^3

$$
$$
\frac{V_{T}}{V} = \frac{1}{48}*\frac{3}{4}=\frac{1}{64}

$$
As we can see, a sphere of half the radius of the original does not have a volume 1/4 of the original sphere, but instead has a volume 1/64 the original sphere. This is because to calculate the volume, every value of the radius is cubed, and the value of the ratio Vt/V effectively cancels out the radius. 

This is why for a tumor with a radius of **2.5 cm**, after heating up 1/4 the radius, the effective portion of the volume that is heated above temperature T is still 1/64, or 1.5625%.



| **Radius of tumor that has reached an effective temperature** | $$V_t \: \: \: $$ | $$\frac{V_t}{V}\: \: \: \: \: \: $$ |
| ------------------------------------------------------------- | ----------------- | ----------------------------------- |
| $$\frac{1}{4}r$$                                              | $$1/48r^3$$       | $$\frac{1}{64}$$                    |
| $$\frac{1}{3}r$$                                              | $$4/81r^3$$       | $$\frac{1}{27}$$                    |
| $$\frac{1}{2}r$$                                              | $$1/6r^3$$        | $$\frac{1}{8}$$                     |
| $$\frac{2}{3}r$$                                              | $$32/81r^3$$      | $$\frac{8}{27}$$                    |
| $$\frac{3}{4}r$$                                              | $$9/16r^3$$       | $$\frac{27}{64}$$                   |
| $$r$$                                                         | $$4/3r^3$$        | $$1$$                               |

As the table above suggests, the ratio of Vt to V is always the coefficient of the given radius of the tumor cubed. 

Looking at the graph, the ratio of Vt/V for when the temperature has reached an effective level equivalent to half the radius is not 1/2, but rather 1/8. 

For a spherical tumor with ratio Vt/V, Vt/V is essentially the coefficient cubed of r. We find the coefficient, or the portion of r by setting up an equation to find the portion of. that has been heated when Vt/V=1/2:

$$
\frac{1}{2}=x^3, \:\:x=0.793701.

$$
The same procedure applies to find the heated portion of r that is Vt/V=3/4:
$$
\frac{3}{4}=x^3, \:\:x=0.90856.
$$












---------------------

### III. A Tumor Modeled by a Wrinkled Sphere

**Wrinkled Sphere:**

![Screen Shot 2025-02-26 at 9.21.09 PM.png|410](/img/user/Screen%20Shot%202025-02-26%20at%209.21.09%20PM.png)

We can estimate the volume of the wrinkly sphere by imagining it as a simple sphere of average radius of 0.5. Therefore, we plug in the formula for a sphere to get:

$$
V_{estimate}=\frac{4}{3}\pi r^3=\frac{4}{3}\pi(0.5)^3=0.523599.
$$

##### Next, we shall integrate the volume of the wrinkly sphere:

$$
V=\int_{0}^{2\pi}\int_{0}^{\pi}\int_{0}^{0.5+0.345sin8\theta sin\phi}\rho
{ #2sin}
\phi \: \: \: d\rho d\phi d\theta
$$
$$
=\frac{1}{3}\int_{0}^{2\pi}\int_{0}^{\pi}(0.5+0.345sin8\theta sin\phi)
{ #3sin}
\phi \: \: \: d\phi d\theta.
$$
$$
=\frac{1}{3}\int_{0}^{2\pi}\int_{0}^{\pi}0.345^3sin^3(8\theta)sin^4(\phi)+3(0.5)(0.345)^2 sin^2(8\theta)sin^3(\phi)+3(0.5)^2(0.345)sin(8\theta)sin^2(\phi)+0.5^3sin(\phi) \: \: \: d\rho d\phi d\theta
$$

$$
 _{scroll \: to\:see\:full\:integral}
$$

We can separately apply the **Wallis' formula** to each term and differentiate with respect to **phi**:
___

$$
\int_{0}^{\pi}sin^4(\phi)d\phi=2\int_{0}^{\frac{\pi}{2}}sin^4(\phi)d\phi=2*\frac{1}{2}*\frac{3}{4}*\frac{\pi}{2}=\frac{3\pi}{8}
$$
____

$$
\int_{0}^{\pi}sin^3(\phi)d\phi=2\int_{0}^{\frac{\pi}{2}}sin^3(\phi)d\phi=2*\frac{2}{3}=\frac{4}{3}
$$
____

$$
\int_{0}^{\pi}sin^2(\phi)d\phi=2\int_{0}^{\frac{\pi}{2}}sin^2(\phi)d\phi=2*\frac{1}{2}*\frac{\pi}{2}=\frac{\pi}{2} .

$$
___

Also,
$$
\int_{0}^{\pi}sin(\phi)d\phi=-cos(\phi)\Bigg|_{0}^{\pi} =-(-1-1)=2.
$$

___

##### Keeping these in mind, we plug the values back and to complete the integration with respect to phi, yielding:
$$
V=\frac{1}{3}\int_{0}^{2\pi}0.345^3(\frac{3\pi}{8})\sin^3(8\theta)+4(0.5)(0.345)^2 \sin^2(8\theta)+3(\frac{\pi}{2})(0.5)^2(0.345)\sin(8\theta)+2(0.5^3) \: \: \: d\theta.
$$
##### Now we will move on to integrating with respect to **theta**. Evaluating theta components separately in each term, we get:
___


$$
\int_{0}^{2\pi}0.345^3(\frac{3\pi}{8})\sin^3(8\theta)d\theta=\int_{0}^{2\pi}0.345^3(0.5)(\frac{3\pi}{8})\sin(8\theta)*(1-\cos^2(8\theta))d\theta
$$
$$=-\frac{1}{8}\cos(8\theta)+\frac{1}{24}\cos^3(8\theta)\Bigg|_{0}^{2\pi}=0
$$


___

$$
\int_{0}^{2\pi}4(0.5)(0.345)^2 \sin^2(8\theta)d\theta=\int_{0}^{2\pi}2(0.5)(0.345)^2(1-\cos(16\theta))d\theta=
$$
$$
0.119025(\theta-\frac{1}{16}sin(16\theta))\Bigg|_{0}^{2\pi}=(0.119025)2\pi=0.747856
$$

___


$$
\int_{0}^{2\pi}3(\frac{\pi}{2})(0.5)^2(0.345)\sin(8\theta)d\theta=-\frac{3}{16}\pi(0.5)^2(0.345)\cos(8\theta)\Bigg|_{0}^{2\pi}=-(1-1)*\frac{3}{16}\pi(0.5)^2(0.345)=0
$$

$$
\int_{0}^{2\pi}2(0.5^3)d\theta=2(2\pi)*0.5^3=1.5708
$$


___

**Adding** all the integrals together, we will get:

$$
V=\frac{1}{3}\int_{0}^{2\pi}0.345^3(\frac{3\pi}{8})\sin^3(8\theta)+4(0.5)(0.345)^2 \sin^2(8\theta)+3(\frac{\pi}{2})(0.5)^2(0.345)\sin(8\theta)+2(0.5^3) \: \: \: d\theta
$$
$$
=\frac{1}{3}(0 + 0.747856+1.5708) = \frac{2.31866}{3}
$$
$$
V=0.772885.
$$

Integrating using the **calculator**, we will get a volume of **0.772884**, which is pretty close to the integrated result. 

Comparing our original estimated volume to our actual volume, we find that there is a percentage error of:
$$
\Bigg|\frac{0.523599-0.772885}{0.772885}\Bigg|\times 100\%=32.254\%.
$$
Although it could be improved, my estimate is somewhat decent. 












---------------------

### IV. A Tumor Modeled by a Bumpy Sphere

***Bumpy Sphere:***

![Screen Shot 2025-02-26 at 8.48.25 PM.png|450](/img/user/Screen%20Shot%202025-02-26%20at%208.48.25%20PM.png)


Integrating the volume of the bumpy sphere, we get:
$$
V=\int_{0}^{2\pi}\int_{0}^{\pi}\int_{0}^{0.75+0.35sin8\theta sin4\phi}\rho
{ #2sin}
\phi \: \: \: d\rho d\phi d\theta
$$

$$
V=\frac{1}{3}\int_{0}^{2\pi}\int_{0}^{\pi}(0.75+0.35sin8\theta sin4\phi)
{ #3sin}
\phi \: \: \: d\phi d\theta.
$$

##### Expanding the integral, we get:

$$
V=\frac{1}{3}\int_{0}^{2\pi}\int_{0}^{\pi} 0.35^3\sin^3(8\theta)\sin^3(4\phi)\sin(\phi)+3*0.35^2*0.75\sin^2(8\theta)\sin^2(4\phi)\sin(\phi)+3*0.035*0.75^2\sin(8\theta)\sin(4\phi)\sin(\phi
) + 0.75^3sin(\phi)\: \: \: d\phi d\theta
$$
$$
 _{scroll \: to\:see\:full\:integral}
$$
##### Evaluating each phi-component term separately with respect to **phi**, we get:

$$
\int_{0}^{\pi} \sin^3(4\phi)\sin(\phi)d\phi = \int_{0}^{\pi} (1-\cos^2(4\phi))sin(\phi)sin(4\phi)d\phi= \int_{0}^{\pi} \sin(\phi)\sin(4\phi)d\phi-\int_{0}^{\pi}\cos^2(4\phi)sin(\phi)sin(4\phi)d\phi
$$
$$
 _{scroll \: to\:see\:full\:integral}
$$
We know that:

$$

\int_{0}^{\pi} \sin(4\phi)\sin(\phi)d\phi=\int_{0}^{\pi}\frac{1}{2}(cos(3\phi)-cos(5\phi))d\phi=\frac{1}{2}(\frac{1}{3}\sin(3\phi)-\frac{1}{5}\sin(5\phi))\Bigg|_{0}^{\pi}=0
$$

so we are left with evaluating

$$
-\int_{0}^{\pi}\cos^2(4\phi)sin(\phi)sin(4\phi)d\phi=-\frac{1}{2}\int_{0}^{\pi}(1+\cos(8\phi))sin(4\phi)sin(\phi)d\phi
$$
$$=-\frac{1}{2}\int_{0}^{\pi}sin(4\phi)sin(\phi)d\phi-\frac{1}{2}\int_{0}^{\pi}   \cos(8\phi)sin(4\phi)sin(\phi)d\phi.
$$
From before, we've shown that 

$$
-\frac{1}{2}\int_{0}^{\pi}sin(4\phi)sin(\phi)d\phi=0,
$$
so we are only left with evaluating 
$$
-\frac{1}{2}\int_{0}^{\pi}   \cos(8\phi)sin(4\phi)sin(\phi)d\phi=-\frac{1}{4}\int_{0}^{\pi} \sin\phi \sin(12\phi)+sin\phi\sin(-4\phi)d\phi
$$
$$
=-\frac{1}{8}\int_{0}^{\pi}\cos(11\phi)-\cos(13\phi)+\cos(5\phi)-\cos(-3\phi)\:\: d\phi
$$
$$
=-\frac{1}{8}\Bigg(\frac{1}{11}\sin(11\phi)-\frac{1}{13}\sin(13\phi)-\frac{1}{5}\sin(5\phi)+\frac{1}{3}\sin(-3\phi)\Bigg)\Bigg|_{0}^{\pi}=0.
$$


___


$$
\int_{0}^{\pi}\sin^2(4\phi)\sin(\phi)d\phi = \int_{0}^{\pi}\frac{1}{2}sin\phi(1-cos(8\phi))d\phi=\frac{1}{2}\int_{0}^{\pi}\sin\phi d\phi\: -\frac{1}{2}\int_{0}^{\pi}sin\phi\cos(8\phi)d\phi
$$
$$
\frac{1}{2}\int_{0}^{\pi}\sin\phi d\phi=-\frac{1}{2}cos\phi\Bigg|_{0}^{\pi}=-\frac{1}{2}(-1-1)=1,
$$

and
$$
-\frac{1}{2}\int_{0}^{\pi}sin\phi\cos(8\phi)d\phi=-\frac{1}{2}\int_{0}^{\pi}\frac{1}{2}(sin(9\phi)+sin(-7\phi))d\phi=-\frac{1}{4}(-\frac{1}{9}cos(9\phi)+\frac{1}{7}cos(-7\phi))\Bigg|_{0}^{\pi}
$$
$$
=-\frac{1}{4}(-2)+\frac{1}{7}(-2)=\frac{1}{63}.
$$

Therefore, 
$$
\int_{0}^{\pi}\sin^2(4\phi)\sin(\phi)d\phi = 1+\frac{1}{63}=\frac{64}{63}.
$$



___

$$

\int_{0}^{\pi} \sin(4\phi)\sin(\phi)d\phi=\int_{0}^{\pi}\frac{1}{2}(cos(3\phi)-cos(5\phi))d\phi=\frac{1}{2}(\frac{1}{3}\sin(3\phi)-\frac{1}{5}\sin(5\phi))\Bigg|_{0}^{\pi}=0
$$
___

Last but not least, 

$$\int_{0}^{\pi}\sin\phi d\phi=-cos\phi\Bigg|_{0}^{\pi}=-(-1-1)=2.$$
___

##### Now, we plug the values back and to complete the integration with respect to phi, yielding:

$$
V=\frac{1}{3}\int_{0}^{2\pi} 0.35^3\sin^3(8\theta)(0)+3*0.35^2*0.75\sin^2(8\theta)(\frac{64}{63})+3*0.035*0.75^2\sin(8\theta)(0) + 0.75^3(2)\: \: \:  d\theta
$$
$$
 _{scroll \: to\:see\:full\:integral}
$$
$$
= \frac{1}{3}\int_{0}^{2\pi} 0.28\sin^2(8\theta)+ 0.84375\: d\theta=\frac{1}{3}\int_{0}^{2\pi}0.28(1-cos(16\theta))+0.84375\:d\theta

$$
We will now integrate with respect to **theta**:
$$
=\frac{1}{3}\Bigg(0.28(0.5)(\theta-\frac{1}{16}\sin(16\theta))+0.84375\theta\Bigg)\Bigg|_{0}^{2\pi}=\frac{1}{3}(0.28\pi+0.84375(2\pi))=\frac{6.18108}{3}

$$
$$
=2.06036.
$$
Verifying with a *calculator*, we obtain **2.06036**, which is identical to the answer we obtained through integration. 













_________
Works Cited:






# That's all!





