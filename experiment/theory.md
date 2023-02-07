### Theory
An inductor (L), capacitor (C), and resistor (R) are linked in series in the electrical
<br>circuit, which is powered by an AC voltage supply. The alternating voltage V is
<br>supplied by the voltage source, where
<br>V=Vm sin(ωt)
<br>where,
<br>● Vm is the amplitude of the applied voltage, and
<br>● ω is the frequency of the applied voltage.
<br>If q is the charge on the capacitor and I is the current flowing in the circuit at any
<br>moment t, the voltage equation for the circuit can be written as follows:
<br>Net EMF across the circuit: V (source voltage) = Voltage drop across resistor +
<br>Voltage drop across capacitor + Self-induced Faraday’s emf in the inductor
<br>V=L(di/dt) + IR + q/C
<br>The inductor’s self-inductance is denoted by L.
<br>Substituting alternating voltage for the expression,
<br>Vm sin(ωt) = L(di/dt) + IR + q/C …..(1)
<br>Let us use the analytical method to determine the instantaneous current I or its
<br>matching phase to the applied alternating voltage V. We know that current is
<br>equal to the rate at which electric charge flows per unit of time, i.e.,
<br>I=dq/dt
<br>Differentiating both sides with respect to time, we get:
<br>dI/dt=d
<br>2q/dt
<br>2
<br>The voltage equation in terms of q is obtained by substituting the above value
<br>into equation (1):
<br>Vm sin(ωt) = L(d
<br.2q/dt
<br>2
<br>) + (dq/dt)R + q/C ……(2)
<br>The equation for a forced or damped harmonic oscillator is similar to this
<br>equation. q = qm sin(ωt+θ)
<br>Differentiating both sides with respect to time,
<br>dq/dt = qm ωcos(ωt+θ)
<br>d
<br>2q/dt
<br>2=–qm ω2sin(ωt+θ)
<br>Substituting these values in equation (2),
<br>Vm sin(ωt) = qmω [Rcos(ωt+θ) + (XC–XL)sin(ωt+θ)] …..(3)
<br>Here,
<br>● Capacitive reactance: XC=1/ωC
<br>● Inductive reactance: XL=ωL
<br>● Impedance: Z= √ (R^2 + (|X L - X C |)^ 2)
<br>Vm sin(ωt)=qm ωZ[R/Z cos(ωt+θ) + (XC–XL)/Zsin(ωt+θ)] ……(4)
<br>Consider,
<br>R/Z = cos∅
<br>(XC–XL)/Z = sin∅
<br>Dividing the two equations:
<br>(XC–XL)/R=tan∅
<br>∅=tan
<br>-1
<br>((XC–XL)/R)
<br>Substituting the above values in equation (4):
<br>Vm sin(ωt)=qm ωZ[cos(ωt+θ–∅)]
<br>Comparing the LHS and RHS of this equation, we get
<br>Vm=qm ωZ=Im Z
<br>The current in the LCR circuit,
<br>I=dq/dt
<br>or,
<br>I = qm ωcos(ωt+θ)
<br>I = Im cos(ωt+θ) [where, qm ω=Im]
<br>Since, θ–∅= – π/2
<br>θ= – π/2 + ∅
<br>We get,
<br>I = Im cos(ωt–π/2+∅)
<br>I = Im sin(ωt+∅)
<br>Here, Im=Vm/Z = Vm / √R
<br>2+(XC–XL)
<br>2 and ∅=tan
<br>-1
<br>(XC–XL/R)
<br>● Thus, for θ=0∘ , As a result, the applied voltage and instantaneous current
<br>are in phase
<br>● For θ=90∘ , The applied voltage is out of phase with the instantaneous
<br>current
<h2>Resonance of LCR Circuith</h2>
 <br> It is the condition when the output of a circuit reaches its maximum at a
<br>specific frequency, it is said to be in resonance.The resonance phenomenon is
<br>connected with systems that have a tendency to oscillate at a specific
<br>frequency known as the natural frequency of the system.
<br>We discovered that the amplitudes of voltage, frequency, and current are
<br>related to each other in the following series of LCR circuits:
<br>Im=Vm/Z = Vm / √R
<br>2+(XC–XL)
<br>2
<br>where,
<br>● XC=1/ωC and
<br>● XL=ωL
<br>Im=Vm/Z=Vm / √R
<br>2+(1/ωC−ωL)
<br>2
<br>When the circuit’s impedance is low, the current flowing through it is at its
<br>maximum. To accomplish so, we change the frequency value till we have
<br>XC=XL at a given frequency of ω0 and the impedance,
<br>Z=√ R
<br>2+(XC−XL)
<br>2 = √ R
<br>2+0 = R
<br>Thus, the current will be maximum, i.e. ,
<br>I=Vm/R
<br>ANM
<br>When the series LCR circuit’s impedance, Z=R, equals the resistance. This
<br>frequency ω0 is referred to as the circuit’s resonant frequency.
<br>For, XC=XL
<br>1/ω0C=ω0L Or,
<br>ω0 = 1/√LC
<br>Resonance occurs in a series LCR circuit when the capacitive and inductive
<br>reactances are equal in magnitude but 180 degrees apart in phase.
<br>For the series LCR circuit, the phase difference,
<br>∅=tan
<br>-1
<br>(XC–XL / R)
<br>For, XC=XL
<br>, ∅=0, the circuit is in resonance.
<br>XC>XL
<br>, ∅<0, the circuit is predominately capacitive
<br>XC<XL
<br>, ∅>0, the circuit is predominately i
