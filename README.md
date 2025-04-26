# elec3104-mini-project-3-short-time-spectrum-analyser-p0-solved
**TO GET THIS SOLUTION VISIT:** [ELEC3104 Mini Project 3-Short-time Spectrum Analyser P0 Solved](https://www.ankitcodinghub.com/product/elec3104-p0-solved-3/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124504&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ELEC3104 Mini Project 3-Short-time Spectrum Analyser  P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
TLT-Level 3: Short-time Spectrum Analyser

 You should use the cochlear model that you have designed in TLT-Level 2 to implement a short-time spectrum analyser. The cascaded filters separate the frequency spectrum of interest (96.5 Hz to 20000 Hz) into N (=128) frequency bands.

 In this mini-project we will continue to use two spatial differentiations in order to sharpen the magnitude response of the filters.

 The spatially differentiated filter output is then passed through a hair cell model (a rectifier followed by a first-order lowpass filter). The output of the hair cell model is a measure of energy (E) of the signal in a particular frequency band (i.e: A Spectrum analyser).

Digital filter model of the basilar membraneAssignment Project Exam Help Organ of Corti

OuputEnergy𝐸𝐸𝑚𝑚 is read (switch closed) once every 16 ms or so.

TLT-Level 3: Inner hair cell model

Inner hair cell model

 The model of an inner hair cell is a capacitor model, in which the input voltage corresponds to the spatially differentiated membrane displacement output of the filter bank model.

 Bending the inner hair cell cilia (Half-wave rectification) is simulated by charging of the capacitor and returning to the initial position of the cilia is equivalent to discharging the capacitor. This model is given by the following input-output relationship:

Assignment Projec−2πt 𝑓𝑓𝑐𝑐Exam Help

𝑣𝑣𝑚𝑚[𝑛𝑛] = 1−𝑐𝑐0𝑒𝑒𝑒𝑚𝑚[𝑛𝑛]+𝑐𝑐0𝑣𝑣𝑚𝑚[𝑛𝑛−1] where 𝑐𝑐0 = 𝑒𝑒 𝑓𝑓𝑠𝑠

𝑒𝑒𝑒 𝑛𝑛 is the spatially differentiated displacement after half-wave rectification.

Cut-off frequency (𝑓𝑓𝑐𝑐) of the hair cell model is based on the rate at which the switch is closed. (every 16 ms – 62.5 Hz). Therefore 𝑓𝑓𝑐𝑐 ≤

31.25 𝐻𝐻𝐻𝐻. Let’s choose 𝑓𝑓𝑐𝑐=30Hz; Sampling frequency (𝑓𝑓𝑠𝑠)=48,000Hz;

Are you on the right track?

Apply a sum of two sinusoidal components (5.92 kHz and 1.01 kHz) at the input 𝑥𝑥[𝑛𝑛].

TLT-Level 3: An alternative inner hair cell model

An alternative inner hair cell model

• A second method of implementing the inner hair cell model is shown below:

Accumulate for

Spatially 16 ms Inner hair cell differentiated membrane ∑ p(k)Sampling period (T) = 16 ms + output q(k)

displacement AssignmeHalf-wave rectifier nt Project ExamDelay Helpp(k-1)

Reset after 16 ms T

filter

• Replace the previous hair cell model with the above model.

• What is the main difference between the above hair cell model and the previous hair cell model in slide 4, TLT level 3? Discuss your understanding with your lab demonstrator.

TLT Level 3 : Final Implementation

Final Implementation

• Apply a signal which is a sum of four sinusoids, 1000-2000 samples, of equal amplitude and frequencies of your choice, to the input of the filter bank. Plot the output of your spectrum analyser (i.e the output of each filter in dB against the filter number) at a particular time instant.

• Plot the magnitude spectrum (using FFT) of the input signal and compare it with the filter bank output. Discuss the results

that you get.

Assignment Project Exam Help
