---
title: "B0s → μμγ : DAQ development and Data Analysis of Run 2 CMS Data"
date:   2022-11-9
tags: ["cms", "analysis"]

links:
    report : 'https://athachay.web.cern.ch/athachay/files/public/store/papers/bs2mumuGamm_dp2_report.pdf'
    slides : 'https://athachay.web.cern.ch/athachay/files/public/store/slides/bsToMuMuGamma_report.pdf'

type : "blog"
---

Developed an analysis strategy and trigger for the rare B-Meson decay B0s → μμγ. Involved developing a dedicated low energy photon identification scheme and a new pipeline in data quisition system for CMS experiment.

**Table of Contents**

*   [Introduction](#introduction)
*   [Photon ID](#photon-id)

Introduction
============

With several recent measurements at the LHC hinting at possible violation of lepton flavor universality in the B-meson sector, it is crucial to explore more transitions of type b→sll to search for possible deviation(s) from the prediction(s) of the Standard Model (SM). In this context we are developing a strategy to look for the radiative counterpart of the decay Bs→ 𝞵𝞵, viz., Bs→ 𝞵𝞵𝜸 process. The physics beyond SM is likely to affect the above two transitions in varied ways. Hence measurement of the rates of these two transitions is extremely important.

However identification and analysis of the 3 body decay mode is more challenging than the 2-body decay mode. During the past data taking periods of Run1 and Run2 there was no suitable trigger condition in place for CMS experiment to select Bs→ 𝜇𝜇𝛾 process on-line. Hence we are developing in parallel an analysis strategy to exploit the B-Parking dataset of Run2. For the upcoming Run3 operations of the LHC we have developed a trigger strategy. Additionally, an inclusive dimuon trigger, extending the dimuon mass range, was also developed.

Photon ID
=========

Identification of low transverse momentum Photons from the calorimeter energy deposits is a challenging task in a hadron collider environment. CMS ECAL has noise levels of 30 MeV ( 80 MeV ) in barrel (Endcap) region. Existing photon identification scheme for the CMS is targeted for photons above 8 GeV. CMS have successfully used dedicated customizations to reconstruct photons from Heavy Ion collisions down to 2 GeV, which helped light by light scattering analysis . We develop an identification scheme for identifying photons from p-p collisions , reliable down to 4GeV, using a multivariate technique.This development helps CMS in expanding its reach to rare radiative heavy flavor decays such as Bs0 → 𝜇𝜇𝛾.

