# Fitted Solar-Reflected Dark Matter Spectra

Parameters of fitted curves of normalized solar-reflected dark matter (SRDM) spectra. The curves are fitted from the Monte-Carlo-simulated SRDM spectra in the paper [Solar reflection of dark matter] (https://arxiv.org/abs/2108.10332).

Contact: Haipeng An (anhp@mail.tsinghua.edu.cn) and Haoming Nie (nhm20@mails.tsinghua.edu.cn)

# Normalized Spectra

All the spectra $F_{A_\rho}(E_\chi)$ in the paper [Solar reflection of dark matter] are normalized to one. Therefore, the differential SRDM fluxes with respect to DM kinetic energy $E_\chi$ are

$\frac{\mathrm{d}\Phi_{\text{SRDM}}}{\mathrm{d}E_\chi} = \Phi_{\text{halo}}\times\frac{F_{A_\rho}(E_\chi) A_\rho}{4\pi r_\oplus^2},$

where $\Phi_{\text{halo}}$ is the halo DM mass density, $A_\rho = \pi (4 R_\odot)^2$ is the area of the impact disc, $R_\odot$ is the radius of the Sun, and $r_\oplus$ is the average radius of the Earth's orbit.

# Contact Interaction

For dark matter (DM) coupled with electrons by the contact interaction, we fit the curves with formulae

$F_{A_\rho}(E_\chi) = \frac{A}{1 + (E_\chi/E_c)^\alpha}.$

The results are summarized in the file SRDM_contact_fit.dat. The columns represent (DM masses $m_\chi$ [MeV], cross sections $\sigma_e$ [cm^2], $A$, $E_c$ [eV], $\alpha$). The fits are valid for $E_\chi > \frac{1}{2} m_\chi (0.000733 c)^2$ and $E_\chi$ > 1 eV.

# Light Mediator

For DM coupled with electrons by a light mediator (for example, the dark photon), we fit the curves with formulae

$F_{A_\rho}(E_\chi) = A (E_\chi/100 eV)^{-\alpha} exp(-E_\chi/E_c).$

The results are summarized in the file SRDM_light_fit.dat. The colums represent (DM masses $m_\chi$ [MeV], $\kappa e_D$, $A$, $E_c$ [eV], $\alpha$), where $\kappa$ is the dark photon kinetic mixing parameter, and $e_D$ is the dark charge of DM. The reference cross section is related to $\kappa e_D$ by $\kappa^2 e_D^2 e^2 \mu_e^2/\pi(q_0^2+m_V^2)^2$, where $\mu_e$ is the reduced mass of the DM particle and the electron, $m_V$ is the mass of the dark photon, and $q_0=\alpha_{\text{EM}} m_e$ is a reference momentum transfer. The fits are valid for $E_\chi > \frac{1}{2} m_\chi (0.000733 c)^2$ and $E_\chi$ > 10 eV