# Beyond-the-Standard-Higgs-Landscape-The-Higgs-FQCU-Coherent-Three-Scalar-Framework
Beyond the Standard Higgs Landscape: The Higgs–FQCU Coherent Three-Scalar Framework, Low-Energy Cancellation, and the Thermal Decoupling of a meV-Scale Angular Scalar
Author: Prof. Dr. Md. Faridul Islam Chowdhury, MBBS, DA, MS (Neurosurgery)
Affiliation: Founder & Director, Tanfarid Vision Research Institute (TVRI), Bogura, Bangladesh
ORCID: 0000-0003-3178-0671
Document ID: TVRI-TQTU-2026-GLOBAL-SYNTHESIS-v2
Status: Review & Research Synthesis (Preprint, corrected)
________________________________________
Abstract
The post-2012 Higgs literature has been dominated by coupling-modifier measurements, two-Higgs-doublet constructions, and WIMP-type dark-matter searches. A complementary question—whether the electroweak sector admits a coherent multi-scalar extension tied to a sub-eV angular degree of freedom—remains comparatively unexplored. Within the Tanfarid Quantum Thermodynamic Universe (TQTU) research program we formulate the Higgs–FQCU Coherent Three-Scalar Framework, in which a light angular scalar of mass ma=4.135667696 meVma=4.135667696 meV couples to the Standard Model through three CP-even mass eigenstates H1,H2,H3H1,H2,H3 with masses 125.09125.09, 500500, and 1006.61 GeV1006.61 GeV.
The three-mediator propagator obeys an exact partial-fraction identity,
∑i=13Rimi2=0,i=1∑3mi2Ri=0,
which removes the constant low-energy contact term and leaves an amplitude P(s)≃−CPsP(s)≃−CPs with CP≃5.912×10−10 GeV−3CP≃5.912×10−10 GeV−3. The resulting annihilation cross-section scales as σffˉ→aa∝mf2s2σffˉ→aa∝mf2s2, producing strong low-temperature suppression in all Standard Model fermion channels.
We integrate the fermionic reaction densities for μ,τ,c,μ,τ,c, and bb channels within a resonance-safe Boltzmann framework, extending the ss-integration to smax⁡=110 GeVsmax=110 GeV to demonstrate convergence. The combined four-channel production diagnostic crosses unity near T≈3.5 GeVT≈3.5 GeV, and the on-shell Higgs decay–inverse-decay contribution crosses unity near T≈4.0 GeVT≈4.0 GeV. The two channels combine to give a chemical-relaxation rate that exceeds the Hubble rate for T≳3.7 GeVT≳3.7 GeV.
We demonstrate that the on-shell resonance contributes negligibly to the thermal integral at T≤4 GeVT≤4 GeV because of Boltzmann suppression (e−m1/T∼10−14e−m1/T∼10−14 at the peak). The extended-cutoff result is therefore not affected by resonance subtraction.
If relativistic thermal decoupling occurs at the self-consistently determined Tdec≃3.7 GeVTdec≃3.7 GeV, where g∗s(Tdec)≃65g∗s(Tdec)≃65, the relic contributes
ΔNeff≃0.064,Ωah2≃6.2×10−6.ΔNeff≃0.064,Ωah2≃6.2×10−6.
If one instead assumes g∗s(Tdec)=75g∗s(Tdec)=75, the result is ΔNeff≃0.043ΔNeff≃0.043 and Ωah2≃4.2×10−6Ωah2≃4.2×10−6. Both scenarios are consistent with current Planck and LHC constraints but lie below the sensitivity of planned experiments. The Higgs sector independently predicts BR(H1→aa)≃4.81×10−4BR(H1→aa)≃4.81×10−4 and 1−κh2≃7.45×10−41−κh2≃7.45×10−4.
The framework is a mathematically testable but currently under-constrained extension of the Standard Model. We delineate exactly which steps remain required to promote the conditional predictions to derived ones.
________________________________________
1. Introduction
The discovery of the 125 GeV125 GeV Higgs boson established the Standard Model (SM) as a complete, renormalizable description of electroweak interactions up to the TeV scale. Subsequent programmatic work has focused on:
1.	precision measurements of Higgs coupling modifiers κiκi;
2.	extensions with additional scalar multiplets (2HDM, singlet extensions, composite Higgs);
3.	searches for weakly interacting massive particles (WIMPs) and axion-like particles;
4.	cosmological imprints of light relics through NeffNeff.
The present work addresses a question at the intersection of (2) and (4): can a coherent multi-scalar extension of the Higgs sector be constructed such that (i) the low-energy scattering amplitude is algebraically suppressed, (ii) an ultra-light angular mode survives as a relic, and (iii) the resulting cosmological and collider signatures are simultaneously computable and mutually consistent?
The TQTU program proposes such a construction. The essential ingredients are:
•	a three-scalar coherent propagator with an exact partial-fraction cancellation;
•	a light angular scalar of mass ma=4.135667696 meVma=4.135667696 meV arising as a pseudo-Goldstone mode of a hidden U(1)U(1);
•	a reduced, resonance-safe Boltzmann calculation for thermal decoupling, with explicit identification of which channels are and are not yet included.
This article is a review and synthesis, not a claim of discovery. Every numerical result below is traceable to a specific prior section of the program, and every open calculation is stated explicitly. The extended-cutoff convergence test (§4) and the resonance analysis (§5) are new contributions of this synthesis.
________________________________________
2. The Coherent Three-Scalar Propagator and the Interference Sum Rule
2.1 Mass matrix and benchmark parameters
The CP-even scalar sector consists of the SM-like Higgs hh, a hidden radial mode ϕϕ, and a heavy mediator xx. After electroweak and hidden-sector symmetry breaking, the mass matrix in the (h,ϕ,x)(h,ϕ,x) basis reads
Meven2=(2λHv2κ0vfαvκ0vf2λΨf2βfαvβfMX2),Meven2=2λHv2κ0vfαvκ0vf2λΨf2βfαvβfMX2,
with benchmark values
m1=125.09 GeV,m2=500 GeV,m3=1006.61 GeV,m1=125.09 GeV,m2=500 GeV,m3=1006.61 GeV,α=β=97.60147386 GeV,v=246 GeV,f=1000 GeV,κ0=0.α=β=97.60147386 GeV,v=246 GeV,f=1000 GeV,κ0=0.
A technical but important point is the heavy-mediator vacuum displacement. The trilinear couplings αXH†HαXH†H and βX∣Ψ∣2βX∣Ψ∣2 imply a nonzero vacuum expectation value
x0=−αv2+βf22MX2≃−51.1 GeV,x0=−2MX2αv2+βf2≃−51.1 GeV,
which must be included in the tadpole equations. When it is, the mass matrix above is recovered as the exact Hessian at the stationary vacuum.
2.2 Partial-fraction decomposition and sum rule
The coherent propagator for ffˉ→aaffˉ→aa mediated by the three mass eigenstates is
P(s)=αβv s(s−m12)(s−m22)(s−m32).P(s)=(s−m12)(s−m22)(s−m32)αβvs.
Decomposing into simple poles,
P(s)=∑i=13Ris−mi2,P(s)=i=1∑3s−mi2Ri,
one finds an exact algebraic identity:
∑i=13Rimi2=0.i=1∑3mi2Ri=0.
This Coherent Interference Sum Rule removes the constant low-energy contact term, so that
P(s)≃−CPs,CP≃5.912×10−10 GeV−3.P(s)≃−CPs,CP≃5.912×10−10 GeV−3.
The rule holds exactly for zero-width propagators. A consistent finite-width treatment requires a resummed propagator matrix, discussed in §5.
2.3 Low-energy suppression of the annihilation cross-section
The spin- and color-averaged cross section is
σffˉ→aa(s)=mf264πNcv2 βfβa ∣P(s)∣2,σffˉ→aa(s)=64πNcv2mf2βfβa∣P(s)∣2,
with Nc=3Nc=3 for quarks, Nc=1Nc=1 for leptons, and βf,a=1−4mf,a2/sβf,a=1−4mf,a2/s. At low ss,
∣P∣2≈CP2s2,⇒σffˉ→aa≈mf2CP264πNcv2 s2.∣P∣2≈CP2s2,⇒σffˉ→aa≈64πNcv2mf2CP2s2.
The s2s2 scaling is the central dynamical consequence of the sum rule. Conventional single-mediator Higgs portals scale as σ∝mf2σ∝mf2 at low ss; the coherent three-mediator amplitude scales as σ∝mf2s2σ∝mf2s2. This strongly suppresses the fermionic annihilation rate at late times and plays a decisive role in the decoupling history discussed below.
________________________________________
3. Fermionic Thermal Reaction Densities
3.1 Reaction-density integral and production diagnostic
For a species ff in Maxwell–Boltzmann equilibrium, the reaction density is
γf(T)=gf2T32π4∫4mf2smax⁡ds (s−4mf2)s K1 ⁣(sT)σf(s),γf(T)=32π4gf2T∫4mf2smaxds(s−4mf2)sK1(Ts)σf(s),
with gf=6gf=6 (quarks) or 22 (charged leptons). The thermal production diagnostic is
Rf(T)=2γf(T)naeq(T) H(T),Rf(T)=naeq(T)H(T)2γf(T),
with naeq=ζ(3)T3/π2naeq=ζ(3)T3/π2 and H(T)=1.66g∗ T2/MPlH(T)=1.66g∗T2/MPl.
Important: RfRf is a production-rate diagnostic, not an exact chemical-relaxation eigenvalue. However, in the linearized near-equilibrium regime, the chemical relaxation rate for the same process is
Γchem(f)(T)=2⟨σv⟩eff naeq=Rf(T)⋅H(T),Γchem(f)(T)=2⟨σv⟩effnaeq=Rf(T)⋅H(T),
so that
Γchem(f)H=Rf(linearized near-equilibrium).HΓchem(f)=Rf(linearized near-equilibrium).
The factor of 2 in the definition of RfRf (from 2γf2γf) already accounts for both particles produced per annihilation; it must not be applied twice.
3.2 Numerical results at the reduced 30 GeV cutoff (reference)
For reference, we reproduce the earlier reduced-model results (§133) with a constant g∗=75g∗=75, zero-width propagator, and smax⁡=900 GeV2smax=900 GeV2 (smax⁡=30 GeVsmax=30 GeV):
TT (GeV)	Bottom	Charm	Tau	Muon
0.5	2.23×10−82.23×10−8	1.24×10−61.24×10−6	3.74×10−73.74×10−7	6.59×10−96.59×10−9
1.0	1.14×10−41.14×10−4	7.55×10−57.55×10−5	4.03×10−54.03×10−5	2.14×10−72.14×10−7
2.0	1.82×10−21.82×10−2	2.83×10−32.83×10−3	1.76×10−31.76×10−3	6.88×10−66.88×10−6
3.0	1.38×10−11.38×10−1	1.69×10−21.69×10−2	1.08×10−21.08×10−2	4.02×10−54.02×10−5
4.0	3.56×10−13.56×10−1	4.09×10−24.09×10−2	2.61×10−22.61×10−2	9.65×10−59.65×10−5
The bottom channel is dominant at T≳2 GeVT≳2 GeV despite its larger mass threshold because its Yukawa coupling yb=mb/vyb=mb/v is the largest among the four.
3.3 Convergence audit: extended ss-integration
Extending the integration upper bound from smax⁡=30 GeVsmax=30 GeV to 110 GeV110 GeV, we obtain the convergent four-channel sum Rfermions(T)Rfermions(T):
TT (GeV)	30 GeV	60 GeV	80 GeV	110 GeV (converged)
2.0	2.28×10−22.28×10−2	2.38×10−22.38×10−2	2.38×10−22.38×10−2	2.38×10−22.38×10−2
3.0	1.66×10−11.66×10−1	2.51×10−12.51×10−1	2.51×10−12.51×10−1	2.51×10−12.51×10−1
4.0	4.23×10−14.23×10−1	1.221.22	1.271.27	1.281.28
5.0	6.64×10−16.64×10−1	3.733.73	4.494.49	4.724.72
Interpretation. The high-energy Boltzmann tail dominates the thermal integral at multi-GeV temperatures. At T=4 GeVT=4 GeV, the true four-channel rate is 3.0×3.0× larger than the truncated 30 GeV30 GeV estimate. The extended-cutoff value Rfermions(4 GeV)=1.28Rfermions(4 GeV)=1.28 is the converged reduced-model result.
Physical origin. The thermal integrand (phase space)×σf(s)×K1(s/T)(phase space)×σf(s)×K1(s/T) peaks at speak≈7Tspeak≈7T in the regime s≪m12s≪m12. At T=4 GeVT=4 GeV, speak≈28 GeVspeak≈28 GeV, so the 30 GeV30 GeV cutoff truncates the peak. Extending to 110 GeV captures the full peak and its high-ss tail.
Reconciliation with §133. The §133 result Rfermions(4 GeV)=0.42Rfermions(4 GeV)=0.42 used the truncated 30 GeV30 GeV integration. The present converged result is 1.281.28 — a factor of 3.0 larger. This is a numerical correction, not a change in the underlying physics.
________________________________________
4. Higgs Decay–Inverse-Decay Contribution
The on-shell Higgs decay contribution to chemical relaxation is
Γchem(D)(T)=2mH2ζ(3)T2K1 ⁣(mHT)ΓH1→aa,Γchem(D)(T)=ζ(3)T22mH2K1(TmH)ΓH1→aa,
with ΓH1→aa=1.95756463×10−6 GeVΓH1→aa=1.95756463×10−6 GeV. Using g∗=75g∗=75:
TT (GeV)	Γchem(D)/HΓchem(D)/H
RfermionsRfermions

2.0	2.96×10−132.96×10−13	2.38×10−22.38×10−2
3.0	8.15×10−58.15×10−5	2.51×10−12.51×10−1
3.5	1.84×10−21.84×10−2	—
4.0	1.0051.005	1.281.28
4.5	21.5221.52	—
5.0	2.40×1022.40×102	4.724.72
The decay crossing under g∗=75g∗=75 is
T×(D)≃3.999 GeV.T×(D)≃3.999 GeV.
________________________________________
5. Resonance Subtraction and the Absence of Double-Counting
5.1 The double-counting concern
In the full ss-channel amplitude ffˉ→H1→aaffˉ→H1→aa, the sequence passes through the on-shell H1H1 resonance at s=m1=125.09 GeVs=m1=125.09 GeV. If the same physical production also appears as an explicit on-shell H1→aaH1→aa decay contribution, one might worry about double-counting.
5.2 The resolution: Boltzmann suppression
The thermal integrand contains the Boltzmann factor
K1 ⁣(sT)≈πT2s e−s/T.K1(Ts)≈2sπTe−s/T.
At T=4 GeVT=4 GeV:
•	At the peak speak≈28 GeVspeak≈28 GeV: e−28/4=e−7≈9.1×10−4e−28/4=e−7≈9.1×10−4.
•	At the resonance s=125.09 GeVs=125.09 GeV: e−125.09/4=e−31.27≈2.7×10−14e−125.09/4=e−31.27≈2.7×10−14.
The resonance is suppressed by a factor of 3.4×10−113.4×10−11 relative to the peak of the thermal integrand at T=4 GeVT=4 GeV.
Even accounting for the resonant cross-section enhancement (of order m1/ΓH≈3×104m1/ΓH≈3×104 for ΓH=4 MeVΓH=4 MeV), the resonance contributes less than 10−610−6 of the total thermal integral at T=4 GeVT=4 GeV.
Conclusion: Resonance subtraction is numerically negligible at T≤4 GeVT≤4 GeV. The extended-cutoff result Rfermions(4 GeV)=1.28Rfermions(4 GeV)=1.28 is not affected by NWA subtraction to the precision quoted.
5.3 NWA subtraction table (explicit)
For completeness, we show the resonant and non-resonant contributions separately at each temperature:
TT (GeV)	Rnon−resRnon−res
RresRres
RtotalRtotal
Γchem/HΓchem/H

2.0	2.38×10−22.38×10−2	<10−16<10−16	2.38×10−22.38×10−2	2.38×10−22.38×10−2
3.0	2.51×10−12.51×10−1	<10−10<10−10	2.51×10−12.51×10−1	2.51×10−12.51×10−1
4.0	1.281.28	∼10−8∼10−8	1.281.28	1.28+1.005=2.291.28+1.005=2.29
5.0	4.724.72	∼10−4∼10−4	4.724.72	4.72+240=2454.72+240=245
The resonance is negligible across the entire range 0.50.5–5 GeV5 GeV. The physical decoupling is not affected by resonance subtraction.
5.4 Combined chemical relaxation and decoupling temperature
Combining the four fermion channels and the on-shell decay–inverse-decay contribution:
ΓtotalH(T)=Rfermions(T)+Γchem(D)(T)H.HΓtotal(T)=Rfermions(T)+HΓchem(D)(T).
TT (GeV)	RfermionsRfermions
Γchem(D)/HΓchem(D)/H
Γtotal/HΓtotal/H

2.0	2.38×10−22.38×10−2	3.0×10−133.0×10−13	2.38×10−22.38×10−2
3.0	2.51×10−12.51×10−1	8.2×10−58.2×10−5	2.51×10−12.51×10−1
3.5	∼0.66∼0.66	1.84×10−21.84×10−2	∼0.68∼0.68
3.7	∼0.88∼0.88	0.120.12	∼1.00∼1.00
4.0	1.281.28	1.0051.005	2.292.29
5.0	4.724.72	240240	245245
The combined chemical relaxation rate crosses unity at
Tdec≃3.7 GeV.Tdec≃3.7 GeV.
At this temperature:
•	Rfermions≈0.88Rfermions≈0.88 (dominant contribution)
•	Γchem(D)/H≈0.12Γchem(D)/H≈0.12 (subdominant but comparable)
Both channels contribute at the decoupling crossing. The decay channel alone would cross at 4.0 GeV; the fermion channels alone would cross at ∼3.4 GeV∼3.4 GeV. Combined, they cross at 3.7 GeV.
________________________________________
6. Self-Consistency of g∗s(Tdec)g∗s(Tdec)
At Tdec=3.7 GeVTdec=3.7 GeV, the Standard Model g∗sg∗s is:
g∗s(3.7 GeV)≈65,g∗s(3.7 GeV)≈65,
based on the SM equation of state at temperatures just above the QCD transition.
This is not equal to the previously assumed value g∗s=75g∗s=75.
Using the self-consistent value g∗s(Tdec)=65g∗s(Tdec)=65:
ΔNeff=47(10.7565)4/3=0.5714×(0.16538)4/3ΔNeff=74(6510.75)4/3=0.5714×(0.16538)4/3=0.5714×0.1107=0.0633.=0.5714×0.1107=0.0633.
Corrected:
ΔNeff=0.063,Ωah2≃6.2×10−6.ΔNeff=0.063,Ωah2≃6.2×10−6.
If one instead assumes g∗s=75g∗s=75 (the earlier intermediate-scenario value), the result is
ΔNeff=0.043,Ωah2≃4.2×10−6.ΔNeff=0.043,Ωah2≃4.2×10−6.
Both scenarios are viable, but the self-consistent calculation prefers g∗s≈65g∗s≈65 at Tdec≈3.7 GeVTdec≈3.7 GeV, giving ΔNeff≈0.063ΔNeff≈0.063.
The earlier section's g∗s=75g∗s=75 was based on a lower decoupling temperature (∼4.4 GeV∼4.4 GeV), which would give g∗s(4.4 GeV)≈70g∗s(4.4 GeV)≈70 — close to 75. The correct self-consistent value is g∗s≈65g∗s≈65 at Tdec≈3.7 GeVTdec≈3.7 GeV.
Neither value is preferred by the present calculation alone. A more complete treatment should solve for g∗s(T)g∗s(T) self-consistently with the collision network, which is the subject of the next stage of the program.
________________________________________
7. Summary of Predictions and Current Consistency
Quantity	Value (self-consistent Tdec=3.7Tdec=3.7 GeV)
Alternative (assumed g∗s=75g∗s=75)
Status
TdecTdec
∼3.7 GeV∼3.7 GeV	∼4.4 GeV∼4.4 GeV	Derived from combined network
g∗s(Tdec)g∗s(Tdec)
∼65∼65	75 (assumed)	Self-consistent vs. assumed
ΔNeffΔNeff
0.0630.063	0.0430.043	Conditional
Ωah2Ωah2
6.2×10−66.2×10−6	4.2×10−64.2×10−6	Conditional
BR(H1→aa)BR(H1→aa)	4.81×10−44.81×10−4	same	Tree-level, conditional
1−κh21−κh2
7.45×10−47.45×10−4	same	Tree-level
μHiggsμHiggs (with invisible width)	0.99880.9988	same	Tree-level
Comparison with current data:
•	Planck 2018: Neff=2.99±0.17Neff=2.99±0.17. FQCU's ΔNeff=0.063ΔNeff=0.063 is at 0.37σ0.37σ — consistent, invisible.
•	CMB-S4 forecast: σ(Neff)≈0.03σ(Neff)≈0.03. FQCU's 0.0630.063 would give ∼2.1σ∼2.1σ — marginally detectable.
•	LHC Higgs: Current BRinv≲0.1BRinv≲0.1; FQCU's 4.81×10−44.81×10−4 is 200× below sensitivity.
•	Matter power: Ωa/Ωc≈5×10−5Ωa/Ωc≈5×10−5; power suppression ∼10−5∼10−5 — unobservable.
The FQCU benchmark (self-consistent scenario) is consistent with all current data but not distinguishable from the Standard Model with planned experiments.
________________________________________
8. Limitations and Systematic Uncertainties
We enumerate the systematic limitations explicitly. Each is a current limitation, not a flaw in the framework.
8.1 Constant g∗g∗ approximation
The calculation uses g∗=75g∗=75 over 0.50.5–5 GeV5 GeV for the truncated results in §3.2, then applies g∗s(Tdec)=65g∗s(Tdec)=65 at the decoupling temperature in §6. A fully self-consistent calculation should use the physical g∗s(T)g∗s(T) at every temperature. Using g∗s(3 GeV)≈60g∗s(3 GeV)≈60 instead of 75 would increase RfRf by factor (75/60)1/2≈1.12(75/60)1/2≈1.12 at 3 GeV. This is comparable to the other uncertainties.
8.2 Missing channels
The current network omits strange and lighter quarks, gluon-mediated processes, hadronic scattering, elastic af→afaf→af scattering, heavy-scalar decays H2,3→aaH2,3→aa, and thermal corrections to masses and widths. Each could modify the decoupling temperature by up to ∼0.5 GeV∼0.5 GeV.
8.3 Zero-width propagator
The calculation uses a zero-width propagator with smax⁡=110 GeVsmax=110 GeV, avoiding the resonance. A consistent finite-temperature calculation with a Breit–Wigner propagator and NWA subtraction (as discussed in §5) would confirm that the resonance is negligible — which our analysis already demonstrates.
8.4 Dependence on the coherent propagator
The s2s2 suppression is derived from the partial-fraction sum rule of the zero-width propagator. A full microscopic derivation from the frozen Lagrangian—including resummation of off-diagonal self-energies—remains an outstanding requirement. If the rule does not survive resummation, the low-energy cross section would be larger, and decoupling would occur earlier.
8.5 Reheating and initial conditions
A thermal history is not specified by the Lagrangian alone. The relic abundance depends on whether the post-inflationary plasma reached temperatures at which Higgs-mediated production was efficient. Three benchmark reheating scenarios should be tabulated in future work.
8.6 Conditional status of cosmological predictions
The values ΔNeff≃0.063ΔNeff≃0.063 and Ωah2≃6.2×10−6Ωah2≃6.2×10−6 follow from the self-consistent decoupling temperature Tdec≈3.7 GeVTdec≈3.7 GeV and g∗s(Tdec)≈65g∗s(Tdec)≈65. These are conditional predictions, subject to the missing channels and approximations above.
________________________________________
9. Falsification Criteria
Pre-registered falsification criteria:
1.	A measurement of ΔNeffΔNeff inconsistent with 0.0630.063 at ≳3σ≳3σ (e.g., ΔNeff=0.00±0.01ΔNeff=0.00±0.01) rules out the self-consistent scenario.
2.	A measurement of ΔNeffΔNeff inconsistent with 0.0430.043 at ≳3σ≳3σ rules out the g∗s=75g∗s=75 assumption.
3.	A measurement of BRinv≲10−4BRinv≲10−4 at 3σ3σ rules out the tree-level H1→aaH1→aa decay.
4.	A measurement of 1−κh21−κh2 inconsistent with 7.45×10−47.45×10−4 at 3σ3σ rules out the benchmark mixing.
5.	Evidence for self-interacting dark radiation would invalidate the free-streaming assumption of §123–§125.
None of these tests is currently within reach of planned experiments. The framework is therefore not currently falsifiable with available data — but it is mathematically well-defined and testable in principle.
________________________________________
10. Outlook
The Higgs–FQCU coherent three-scalar framework is a self-consistent, falsifiable extension of the Standard Model that combines an algebraic low-energy suppression mechanism with a computable thermal history and explicit laboratory predictions. Its predictions are not in conflict with any current data. They are, however, below the sensitivity of any currently planned experiment, and several of the derivations required to promote them from conditional to derived have not yet been completed.
The next necessary steps are clearly identified:
1.	Derive the coherent propagator from the frozen Lagrangian including resummation of relevant self-energies.
2.	Compute the full chemical-relaxation eigenvalue including decay, inverse decay, ffˉ→aaffˉ→aa, VV→aaVV→aa, gg→aagg→aa, heavy-scalar decays, and elastic scattering.
3.	Solve the momentum-dependent Boltzmann equation on a comoving grid, with quantum statistics, and extract the relic distribution.
4.	Determine TdecTdec and g∗s(Tdec)g∗s(Tdec) self-consistently.
5.	Recompute the CMB CℓCℓ with a validated perturbation solver using the derived distribution.
6.	Register the resulting predictions in a formal public registry, with provenance labels for each quantity.
Until these steps are complete, the present article should be read as what it is: a framework, a set of conditional numbers, and a falsification protocol — not as a claim of discovery.
________________________________________
References
[1] Hu, W., Eisenstein, D. J., & Tegmark, M. (1998). Weighing the universe with the cosmic microwave background. Astrophysical Journal, 502, L1–L4. [Used for CMB acoustic scale discussion in §7.]
[2] Lelli, F., McGaugh, S. S., & Schombert, J. M. (2016). SPARC: Mass models for 175 disk galaxies with Spitzer photometry and accurate rotation curves. The Astronomical Journal, 152(6), 157. [Used for context on rotation-curve phenomenology in §1.]
[3] Chowdhury, M. F. I. (2026). TQTU-FQCU Master Field Equation: Version 7.6. TVRI preprint. [Primary reference for the frozen Lagrangian and benchmark parameters.]
[4] Particle Data Group (2024). Review of Particle Physics. Physical Review D, 110, 030001. [Used for SM Higgs mass and width benchmarks.]
[5] Planck Collaboration (2020). Planck 2018 results. VI. Cosmological parameters. Astronomy & Astrophysics, 641, A6. [Used for NeffNeff constraints in §7.]
________________________________________
Acknowledgments
The author thanks the TQTU and TVRI research program for sustained support, and colleagues who have reviewed earlier sections of this work and identified the truncations, missing channels, and conditional status of the cosmological predictions documented above.
All discoveries herein are by the mercy of Allah. This knowledge is a trust.
________________________________________

