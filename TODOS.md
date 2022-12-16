# TODOS

- [] Add control Lyapunov function and control barrier function to introduction.

-   [x] Learning from demonstrations explanation.

-   [x] Regression methods.

-   [x] Traditional lfd research.
    -   [x] Simple regressions not robust (generalizable).
        -   [x] Overfitting.
        -   [x] Linear stabiel maar niet accurate. 
            -   [x] maar kan alleen rechte paden.
            -   [x] Daarom non-linear.
            -   [x] Maar non-linear niet stabiel/generalizble.
            -   [x] Daarom stability based methods.
    -   [x] Several methods have been proposed to improve stability of the learned models.
        -   [x] Transient non-linear models (DMP).
            -   [x] strengths and shortcomings.
            -   [x] extensions.
        -   [x] Constrained optimization (SEDS).
            -   [x] Strengths and shortcomings.
            -   [x] Extensions
        -   [x] Constraint optimization with neural network (ELM).
            -   [x] Strengths and shortcomings.
            -   [x] Extensions.
        -   [ ] Diffeomorphisms.
            -   [ ] Strengths and shortcomings.
            -   [ ] Extensions.
        -   [ ] Convergence based methods.
            -   [ ] Strengths and shortcomings.

-   [ ] Impedance based LfD methods.
    -   [ ] Combined methods.
    -   [ ] Separate methods.
        -   [ ] Energy tanks.
        -   [ ] Potential fields.
        -   [ ] Lyapunov constraints.


        - Maar het restulaat blijft afhankelijk van hoe coservatief het contraint is.
        
        - Daarom gebruiken andere autheurs diffeomorphism om te learn in de non-lineare space maar het constraint toe te passen in een lineare space.
        - Meerdere methods.
        
        - Maar geen garantie hoe een pad naar het eind punt komt. Daarom nieuwste artikelen convergence based methods.

### OTHER

% TODO: Check Anand et al. 2021.
 TODO: Alshuka, sharifi and song reviews.

% TODO: Model based vs learning based.
% TODO: explain adaptvie or passive controllers.
% TODO: Kronander 2015 shape DS while keeping stability properties of original system.
% TODO: Check landi paper for tank optimization.laa

% TODO: TANKS
% TODO: Non-conservative part of tank is zero conservative part can be tracked (Kronander et al. 2016)
% TODO: Initial energy estimation of tank from training data

% TODO: Measurement of physical interaction might not be possible when learning from demonstrations (balatti 2020).

% TODO: Check Jin for downsides RL vs GGM. JIN 2022 good starting point for this chapter!.

% TODO: Tiseo 2022: Learning based methods not robust or generalizable.

% TODO: Variale impednace leearing (LFD) and Variable impedance learing control (VILC)abu daku.
% TODO: LFD mostly at kinematic level (see ballatti 2020).

% TODO: Check bensi 2022 for earlier papers non manipulator CBF ect.
% TODO: Online learning?

% TODO: ==IMPORTANT PAPERS==
% TODO: Spaandonk thesis for general model based impedance methods.
% TODO: Kronander et al. 2015 shaping DS while keeping stability properties of original system.

% TODO: See si for force articles.
% TODO: Add regression models.

% TODO: Text Overview:
% - DMP: Ijspeert -> improvement articles.
% - SEDS: Khansari -> improvement articles.

% TODO: Mohammad Khansari-Zadeh leans lyapunov function to create a GAS DS.

% TODO: Rana et al. 2020: Stable Learning based DS. Good starting point.

% TODO: Explain sensor methods and modelling methods (DS ect?)

% TODO: Arduengo uses kronander, others use tank based.

% TODO: Jin uses lyapunov optimization.

% TODO: Old methods -> Stability constraint on parameters of DS (see Saveriano et al. 2020) -> Potential fields ()

% TODO: Optimize with constraint but this might lead to decreased performance therefore energy tank (Savariano)!

% TODO: See arduengo for overview of LFD methods.

% TODO: Also check supplementary Learning folder. For safe/stable non-impedance learing

% TODO: Liang 2021: Online RL with constraint on inertia.
% TODO: Kim could be constant impedance?
% TODO: GAILS? INverse RL?
% TODO: Check Zhang et al. 2022

% Give an extension to impedance research.
% SEDS of DMP: Trajectory + GMM for impedance paramters
% GMM voor alles
% DMP voor alles CMP.
%But these methods are rather conservative and do not show passivity when using in interaction. Therefore several authors have used the % % passivity methods in the previous chapters like energy-tanks and lyapunov constraints for ensure passivity.
% List tank-based and Lyapunov constraints.

% TODO: ARTICLES (benzi 2022)
% - Barrier-certified adaptive reinforcement learning with applications to brushbot navigation (Ohnish 2019).
% - Safety-aware reinforcement learning framework with an actor-critic-barrier structure (Yang 2020).
% - Rossi et al., “Cognitive robotic architecture for semi-autonomous execution of manipulation tasks in a surgical environment
% - Learn fast, forget slow: Safe predictive learning control for systems with unknown and changing dynamics performing repetitive tasks

% TODO: Also called imitation learning.
% - Explain what is learning from demonstrations is (Sensors and model).
% - Explain conservative DS and why they are not sufficient.
% - Explain how kronander et al. 2016 uses energy tank to keep conservative DS passive.
% - Give papers that use this techique.
% - Show other methods.
%    Kronander creates a new passive DS that also can encode non-passive actions.
%    Extended by amoud for contact tasks with force tracking.

% DMP: Used for single behavoir, Gaussian methods used for complex behavoir (see kastritsi)

% Check sharifi et al. 2022 for impedance learning.
