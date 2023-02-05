# A-self-adaptive-hardware-with-resistive-switching-synapses-for-experience-based-neurocomputing

Modelling codes for the paper entitled "A self-adaptive hardware with resistive switching synapses for experience-based neurocomputing" published in Nature Communications

In this repository you can find the Matlab-based codes for the work "A SELF-ADAPTIVE HARDWARE WITH RESISTIVE SWITCHING SYNAPSES FOR EXPERIENCE-BASED NEUROCOMPUTING" by Stefano Bianchi, Irene Munoz Martin et al.

Note also that these codes provide general behavioral cases: putting each single test case would have increased confusion in this repository; we have thus decided to provide general codes which, depending on the analysis that are wanted to be carried out, can be simply adapted by a little tuning following the comments reported in the codes: for instance, in order to see the weighted evolution of the maze environment considering the environmental changes, it is necessary to opportunely weight each trial of exploration, or simply targeting a different case study. Note also that the color bars for the color maps have been chosen arbitrarily: changing the color bar axis could help in visualizing different features of the network itself. In every case, the authors of this work can be contacted for providing advice, practical aid and explanation of the implemented system.

All the provided codes are Matlab-based. A version newer, or equal, to the used one (R2019a) is required.The running instructions are reported in each code.

Some of the codes of the work have not been provided, due to the non-disclosure agreements over the hardware built for this work, which is based on SiOx RRAM arrays. However, further codes and data can be asked to the corresponding author upon reasonable request.

The codes provided are the following ones:

1) Codes related to dynamic reinforcement learning for autonomous navigation: it is here demonstrated, by a top-level point of view, the overall functionality of the network. This code is higly flexible and can be accordingly modulated depending on the necessities. In its current status, the code provides the time analysis, policy map creation and exploration capability in a dyanamically changing environment (two excel files with two sample mazes are also provided). Note that the codes have been deprived of sensible technological data related to the RRAM arrays, since the codes themselves have been used as top-level behavioral codes for the hardware realization described in the paper. Note that, depending on the case study, these codes need to be accordingly modulated in order to enable a correct data collection (e.g., the colours have been chosen to highlight the main movement of the agent, discarding secondary features of the agent itself). Note also that, since the code gives visual outputs, some slow-down of the image refresh of the results could happen if the computing graphic power is not enough: let the code running and gather the final results.

2) Codes related to the STDP asynchronous protocol with homeostatic plasticity (also called synaptic scaling). These codes provide better insight over the most relevant firing capabilites of the neurons with adaptive thresholds implemented in this work. In these codes, we also offer the possibility of multi-learning of large patterns, thus demonstrating the theoretical robustness of the proposed implementation.

3) Codes for the optimization of the STDP protocol and for the definition of the most relevant parameters of the homeostatic asynchronous STDP inside the main code

4) Codes for the management of the parameters analyzer for the DC experimental measurements.

5) Codes for the management of the pulser generator for the experimental measurements.

6) Codes for the handshake protocol of the peripherals with the SoC (Zync7000) and with Arduino (some details are not reported due to non-disclosure agreements over the built hardware).

7) Codes for the 8-channel oscilloscope management.

THE SOFTWARES ARE PROVIDED "AS THEY ARE", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
