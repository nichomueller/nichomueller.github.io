@def title = "Achievements"

# Achievements

## A comprehensive library for reduced order modeling in Julia

I am the author of [GridapROM.jl](https://github.com/gridap/GridapROMs.jl), a Julia-based library for the numerical approximation of parameterized partial differential equations using a comprehensive suite of reduced order models. The library is designed to be extendable and productive, leveraging an expressive high-level API, while achieving high performance through Julia's just-in-time compiler and advanced lazy evaluation techniques. GridapROMs is PDE-agnostic, enabling its application to a wide range of problems, including linear, nonlinear, single-field, multi-field, steady, and unsteady equations. 

$$
\begin{center}
	\begin{figure}
		\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

        \begin{tikzpicture}[x=0.6pt,y=0.6pt,yscale=-1,xscale=1]
        %uncomment if require: \path (0,553); %set diagram left start at 0, and has height of 553
        
        %Shape: Rectangle [id:dp6954657244910863] 
        \draw  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][fill={rgb, 255:red, 233; green, 243; blue, 221 }  ,fill opacity=1 ][line width=1.1] (221.42,13.25) -- (565.92,13.25) -- (565.92,70.25) -- (221.42,70.25) -- cycle ; -- cycle ;
        %Shape: Rectangle [id:dp13137619570630787] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][fill={rgb, 255:red, 208; green, 222; blue, 239 }  ,fill opacity=1 ][line width=1.1] (26,96) -- (350,96) -- (350,181.25) -- (26,181.25) -- cycle ;
        %Shape: Rectangle [id:dp9279457397747317] 
        \draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ][fill={rgb, 255:red, 246; green, 221; blue, 221 }  ,fill opacity=1 ][line width=1.1] (15,233.5) -- (363.67,233.5) -- (363.67,296.53) -- (15,296.53) -- cycle ;
        %Rounded Rect [id:dp6954072834272838] 
        \draw  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ] (243,26.65) .. controls (243,23.67) and (245.42,21.25) .. (248.4,21.25) -- (286.6,21.25) .. controls (289.58,21.25) and (292,23.67) .. (292,26.65) -- (292,42.85) .. controls (292,45.83) and (289.58,48.25) .. (286.6,48.25) -- (248.4,48.25) .. controls (245.42,48.25) and (243,45.83) .. (243,42.85) -- cycle ;
        % %Straight Lines [id:da5111036832095992] 
        % \draw    (330,37.25) -- (358,37.25) ;
        % \draw [shift={(361,37.25)}, rotate = 180] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        \draw    (292.31,32.87) -- (342.42,33.23) ;
        \draw [shift={(345.42,33.25)}, rotate = 180.41] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Rounded Rect [id:dp3324062522766814] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.5] (43,118.65) .. controls (43,115.67) and (45.42,113.25) .. (48.4,113.25) -- (115.6,113.25) .. controls (118.58,113.25) and (121,115.67) .. (121,118.65) -- (121,134.85) .. controls (121,137.83) and (118.58,140.25) .. (115.6,140.25) -- (48.4,140.25) .. controls (45.42,140.25) and (43,137.83) .. (43,134.85) -- cycle ;
        %Rounded Rect [id:dp9009616369858544] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.5] (132,118.65) .. controls (132,115.67) and (134.42,113.25) .. (137.4,113.25) -- (218.6,113.25) .. controls (221.58,113.25) and (224,115.67) .. (224,118.65) -- (224,134.85) .. controls (224,137.83) and (221.58,140.25) .. (218.6,140.25) -- (137.4,140.25) .. controls (134.42,140.25) and (132,137.83) .. (132,134.85) -- cycle ;
        %Rounded Rect [id:dp8959437666783153]
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] (38,114) .. controls (38,109.58) and (41.58,106) .. (46,106) -- (221,106) .. controls (225.42,106) and (229,109.58) .. (229,114) -- (229,138) .. controls (229,142.42) and (225.42,146) .. (221,146) -- (46,146) .. controls (41.58,146) and (38,142.42) .. (38,138) -- cycle ;
        %Straight Lines [id:da6890007609364703] 
        \draw    (228,128.25) -- (264,128.25) ;
        \draw [shift={(267,128.25)}, rotate = 180] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Rounded Rect [id:dp09120400885356783] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] (267,119.65) .. controls (267,116.67) and (269.42,114.25) .. (272.4,114.25) -- (331.6,114.25) .. controls (334.58,114.25) and (337,115.67) .. (337,119.65) -- (337,135.85) .. controls (337,138.83) and (334.58,141.25) .. (331.6,141.25) -- (272.4,141.25) .. controls (269.42,141.25) and (267,138.83) .. (267,135.85) -- cycle ;
        %Flowchart: Alternative Process [id:dp43349901088276543] 
        \draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] (42,245.09) .. controls (42,242.65) and (43.98,240.67) .. (46.42,240.67) -- (155.58,240.67) .. controls (158.02,240.67) and (160,242.65) .. (160,245.09) -- (160,261.5) .. controls (160,263.94) and (158.02,265.92) .. (155.58,265.92) -- (46.42,265.92) .. controls (43.98,265.92) and (42,263.94) .. (42,261.5) -- cycle ;
        %Rounded Rect [id:dp7332060720436983] 
        \draw  [color={rgb, 255:red, 208; green, 2; blue, 27 }  ,draw opacity=1 ] (212.31,245.09) .. controls (212.31,242.65) and (214.46,240.67) .. (217.11,240.67) -- (294.84,240.67) .. controls (297.5,240.67) and (299.64,242.65) .. (299.64,245.09) -- (299.64,261.5) .. controls (299.64,263.94) and (297.5,265.92) .. (294.84,265.92) -- (217.11,265.92) .. controls (214.46,265.92) and (212.31,263.94) .. (212.31,261.5) -- cycle ;
        %Shape: Rectangle [id:dp7320503252347348] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][fill={rgb, 255:red, 203; green, 218; blue, 236 }  ,fill opacity=1 ][line width=1.1] (444,96) -- (768,96) -- (768,181.25) -- (444,181.25) -- cycle ;
        %Rounded Rect [id:dp2246777250805826] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.5] (475,118.65) .. controls (475,115.67) and (477.42,113.25) .. (480.4,113.25) -- (547.6,113.25) .. controls (550.58,113.25) and (553,115.67) .. (553,118.65) -- (553,134.85) .. controls (553,137.83) and (550.58,140.25) .. (547.6,140.25) -- (480.4,140.25) .. controls (477.42,140.25) and (475,137.83) .. (475,134.85) -- cycle ;
        %Rounded Rect [id:dp7071389256433379] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][line width=0.5] (571,118.65) .. controls (571,115.67) and (573.42,113.25) .. (576.4,113.25) -- (621.6,113.25) .. controls (624.58,113.25) and (627,115.67) .. (627,118.65) -- (627,134.85) .. controls (627,137.83) and (624.58,140.25) .. (621.6,140.25) -- (576.4,140.25) .. controls (573.42,140.25) and (571,137.83) .. (571,134.85) -- cycle ;
        %Rounded Rect [id:dp6044164971523477] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ] (457,114) .. controls (457,109.58) and (460.58,106) .. (465,106) -- (639,106) .. controls (643.42,106) and (647,109.58) .. (647,114) -- (647,138) .. controls (647,142.42) and (643.42,146) .. (639,146) -- (465,146) .. controls (460.58,146) and (457,142.42) .. (457,138) -- cycle ;
        %Straight Lines [id:da23927762213113912] 
        \draw  [dash pattern={on 0.84pt off 2.51pt}]  (337,129.25) -- (456,128.27) ;
        \draw [shift={(459,128.25)}, rotate = 179.53] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Curve Lines [id:da9176912539667261] 
        \draw    (221.42,40.25) .. controls (181.03,40.25) and (180.43,41.22) .. (180.97,91.9) ;
        \draw [shift={(181,95.25)}, rotate = 268] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Curve Lines [id:da18110120528601026] 
        \draw    (565.42,40.25) .. controls (605.23,40.25) and (605.91,41.22) .. (607.83,91.9) ;
        \draw [shift={(607.92,95.25)}, rotate = 268] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Straight Lines [id:da3042263787483279] 
        \draw    (181.64,183.2) -- (181.64,230.87) ;
        \draw [shift={(181.64,233.87)}, rotate = 270] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;
        %Shape: Rectangle [id:dp5974181310815879] 
        \draw  [fill={rgb, 255:red, 155; green, 155; blue, 155 }  ,fill opacity=0.27 ][dash pattern={on 4.5pt off 4.5pt}] (15,87.75) -- (776,87.75) -- (776,205.75) -- (15,205.75) -- cycle ;
        %Rounded Rect [id:dp2917506861558591] 
        \draw  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ] (345.31,26.65) .. controls (345.31,23.67) and (347.82,21.25) .. (350.91,21.25) -- (471.4,21.25) .. controls (474.49,21.25) and (477,23.67) .. (477,26.65) -- (477,32.85) .. controls (477,45.83) and (474.49,47.25) .. (471.4,48.25) -- (350.91,48.25) .. controls (347.82,48.25) and (345.31,45.74) .. (345.31,42.65) -- cycle ;
        \draw    (160.31,253.87) -- (209.31,253.87) ;
        \draw [shift={(212.31,253.87)}, rotate = 180] [fill={rgb, 255:red, 0; green, 0; blue, 0 }  ][line width=0.08]  [draw opacity=0] (10.72,-5.15) -- (0,0) -- (10.72,5.15) -- (7.12,0) -- cycle    ;

        % Text Node
        \draw (248,28) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {Main.jl};
        % Text Node
        \draw (237,162) node [anchor=north west][inner sep=0.75pt] [font=\footnotesize] [align=left] { \textsc{\textbf{Offline phase}}};
        % Text Node
        \draw (50,247.10) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {Snapshots generation};
        % Text Node
        \draw (49,120) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {RB subspace};
        % Text Node
        \draw (220,247.10) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {HF operations};
        % Text Node
        \draw (458,52) node [anchor=north west][inner sep=0.75pt] [align=left] {\textsc{\textbf{User code}}};
        % Text Node
        \draw (354,28) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {FOM, RB specifications};
        % Text Node
        \draw (138,120) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {Hyper-reduction};
        % Text Node
        \draw (271,121.5) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {RB operator};
        % Text Node
        \draw (480,121) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {RB assembly};
        % Text Node
        \draw (575,121) node [anchor=north west][inner sep=0.75pt]  [font=\scriptsize] [align=left] {RB solve};
        % Text Node
        \draw (660,161) node [anchor=north west][inner sep=0.75pt] [font=\footnotesize] [align=left] { \textsc{\textbf{Online phase}}};
        % Text Node
        \draw (680,187.25) node [anchor=north west][inner sep=0.75pt]  [align=left] {\textsc{\textbf{RB code}}};
        % Text Node
        \draw (184,24) node [anchor=north west][inner sep=0.75pt]  [font=\footnotesize] [align=left] {$\bm{\mu}_{\texttt{off}}$};
        % Text Node
        \draw (578,24) node [anchor=north west][inner sep=0.75pt]  [font=\footnotesize] [align=left] {$\bm{\mu}_{\texttt{on}}$};
        % Text Node
        \draw (267,275.33) node [anchor=north west][inner sep=0.75pt] [align=left] { \textsc{\textbf{HF code}}};
        \end{tikzpicture}	
        \caption{\small A schematic view of the implementation of GridapROMs.}
        \label{fig: GridapROMs implementation}
	\end{figure}
\end{center} 
$$

One of the library's key innovations is the efficient generation of high-fidelity snapshots of parameterized partial differential equations by exploiting lazy evaluations of cell-wise quantities defined on the finite element mesh. Concurrently, the use of message-passing interfaces enables the generation of the snapshots -- datasets of potentially huge sizes, up to billions of entries in time-dependent applications -- also when dealing with very fine spatial and temporal scales. The implementation of the library overcomes the computational bottleneck which the generation of high-fidelity datasets represents. 

$$
\begin{figure}%[H]
	% \vspace{-2cm}
	\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

	\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
        %uncomment if require: \path (0,182); %set diagram left start at 0, and has height of 182

        %Image [id:dp8853776282675806] 
        \draw (82.21,58.25) node  {\includegraphics[scale=0.8]{/assets/cost.png}};

        % Text Node
        \draw (-130,-140) node [anchor=north west][inner sep=0.75pt]  [xscale=1.2,yscale=1.2] [align=left] {\myfont{Residual estimates}};
        % Text Node
        \draw (120,-140) node [anchor=north west][inner sep=0.75pt]  [xscale=1.2,yscale=1.2]  [align=left] {\myfont{Jacobian estimates}};

        % Text Node
        \draw (-180,10) node [anchor=north west][inner sep=0.75pt][rotate=90]  [xscale=1.2,yscale=1.2] [align=left] {\myfont{Time [s]}};
        % Text Node
        \draw (-180,200) node [anchor=north west][inner sep=0.75pt][rotate=90]  [xscale=1.2,yscale=1.2]  [align=left] {\myfont{Memory [Gb]}};

        % Text Node
        \draw (-98,55) node [anchor=north west][inner sep=0.75pt]  [xscale=0.7,yscale=0.7] [align=left] {\myfont{Number of parameters}};
        % Text Node
        \draw (150,55) node [anchor=north west][inner sep=0.75pt]  [xscale=0.7,yscale=0.7]  [align=left] {\myfont{Number of parameters}};

        % Text Node
        \draw (-98,236) node [anchor=north west][inner sep=0.75pt]  [xscale=0.7,yscale=0.7] [align=left] {\myfont{Number of parameters}};
        % Text Node
        \draw (150,236) node [anchor=north west][inner sep=0.75pt]  [xscale=0.7,yscale=0.7]  [align=left] {\myfont{Number of parameters}};

        % %Shape: Circle [id:dp25159401063645714] 
        % \draw  [color={rgb, 255:red, 126; green, 211; blue, 33 }  ,draw opacity=1 ][fill={rgb, 255:red, 126; green, 211; blue, 33 }  ,fill opacity=1 ] (-78,263.63) .. controls (-78,261.76) and (-76.49,260.25) .. (-74.62,260.25) .. controls (-72.76,260.25) and (-71.25,261.76) .. (-71.25,263.63) .. controls (-71.25,265.49) and (-72.76,267) .. (-74.62,267) .. controls (-76.49,267) and (-78,265.49) .. (-78,263.63) -- cycle ;
        %Shape: Circle [id:dp6246135055320745] 
        \draw  [color={rgb, 255:red, 74; green, 144; blue, 226 }  ,draw opacity=1 ][fill={rgb, 255:red, 74; green, 144; blue, 226 }  ,fill opacity=1 ] (-35,260.63) .. controls (-35,258.76) and (-33.49,257.25) .. (-31.62,257.25) .. controls (-29.76,257.25) and (-28.25,258.76) .. (-28.25,260.63) .. controls (-28.25,262.49) and (-29.76,264) .. (-31.62,264) .. controls (-33.49,264) and (-35,262.49) .. (-35,260.63) -- cycle ;
            %Shape: Circle [id:dp25159401063645714] 
        \draw  [color={rgb, 255:red, 82; green, 171; blue, 5 }  ,draw opacity=1 ][fill={rgb, 255:red, 82; green, 171; blue, 5 }  ,fill opacity=1 ] (67,260.63) .. controls (67,258.76) and (68.51,257.25) .. (70.38,257.25) .. controls (72.24,257.25) and (73.75,258.76) .. (73.75,260.63) .. controls (73.75,262.49) and (72.24,264) .. (70.38,264) .. controls (68.51,264) and (67,262.49) .. (67,260.63) -- cycle ;
        %Shape: Circle [id:dp8829816537732889] 
        \draw  [color={rgb, 255:red, 250; green, 152; blue, 12 }  ,draw opacity=1 ][fill={rgb, 255:red, 250; green, 152; blue, 12 }  ,fill opacity=1 ] (167,260.63) .. controls (167,258.76) and (168.51,257.25) .. (170.38,257.25) .. controls (172.24,257.25) and (173.75,258.76) .. (173.75,260.63) .. controls (173.75,262.49) and (172.24,264) .. (170.38,264) .. controls (168.51,264) and (167,262.49) .. (167,260.63) -- cycle ;
        % Text Node
        \draw (-27,253) node [anchor=north west][inner sep=0.75pt]  [xscale=1,yscale=1] [align=left] {$h = 0.07$};
        % Text Node
        \draw (74.5,253) node [anchor=north west][inner sep=0.75pt]  [xscale=1,yscale=1] [align=left] {$h = 0.05$};
        % Text Node
        \draw (174.5,253) node [anchor=north west][inner sep=0.75pt]  [xscale=1,yscale=1] [align=left] {$h = 0.035$};

    \end{tikzpicture}
    \caption{\small Wall time and memory usage for assembling residuals and Jacobians in GridapROMs, applied to a steady-state Navier-Stokes problem in the 3D geometry shown in Fig. \ref{fig: nstokes model}, across varying mesh sizes. The measurements are compared against a baseline cost estimate (solid lines) as a function of the number of parameters. The baseline represents the cost of assembling a single residual/Jacobian using Gridap, scaled by the number of parameters. Note that the estimates exclude the cost of allocating global residuals and Jacobians.}
	\label{fig: cost estimates}
\end{figure}
$$

$$
\begin{figure}%[H]
	% \vspace{-2cm}
	\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

	\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-1,xscale=1]
        %uncomment if require: \path (0,182); %set diagram left start at 0, and has height of 182

        %Image [id:dp8853776282675806] 
        \draw (82.21,45) node  {\includegraphics[scale=0.8]{/assets/error.png}};

        % Text Node
        \draw (-172,-165) node [anchor=north west][inner sep=0.75pt]  [xscale=1.3,yscale=1.3] [align=left] {\myfont{tol} $= 10^{-3}$};
        % Text Node
        \draw (33,-165) node [anchor=north west][inner sep=0.75pt]  [xscale=1.3,yscale=1.3]  [align=left] {\myfont{tol} $= 10^{-4}$};
        % Text Node
        \draw (242,-165) node [anchor=north west][inner sep=0.75pt]  [xscale=1.3,yscale=1.3]  [align=left] {\myfont{tol} $= 10^{-5}$};

        % Text Node
        \draw (-174,-127.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$0$};
        % Text Node
        \draw (-74,-129.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$2 \cdot 10^{-4}$};
        \draw (12.5,-127.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$0$};
        % Text Node
        \draw (111,-129.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$1 \cdot 10^{-5}$};
        % Text Node
        \draw (196.5,-127.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$0$};
        % Text Node
        \draw (295,-129.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$1 \cdot 10^{-6}$};

        % Text Node
        \draw (-210,53) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$-1 \cdot 10^{-2}$};
        % Text Node
        \draw (-74,54.5) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$0$};
        \draw (-24,53) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$-1 \cdot 10^{-3}$};
        % Text Node
        \draw (112,53) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$5 \cdot 10^{-4}$};
        % Text Node
        \draw (160,53) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$-4 \cdot 10^{-4}$};
        % Text Node
        \draw (295,53) node [anchor=north west][inner sep=0.75pt]  [xscale=0.8,yscale=0.8] [align=left] {$1 \cdot 10^{-4}$};

	\end{tikzpicture}
    \caption{\small Point-wise error between the \ac{fe} solution for the parameter $\bm{\mu} = (7.35, 2.00, 4.48)$ at $t = T$ and the corresponding solutions computed with GridapROMs for various tolerances. The first row shows the velocity magnitude errors for tolerances $\{10^{-i}\}_{i=3}^{5}$, while the second row presents the pressure field errors.}
	\label{fig: navier stokes results}
\end{figure}  
$$

## The successful integration of tensor-train decompositions with reduced basis methods

I developed an original reduced basis solver for the efficient solution of parameterized partial differential equations which leverages the tensor-train format to efficiently represent high-dimensional finite element quantities. This method offers several advantages, including a significantly cheaper construction the reduced subspaces, a cost-effective hyper-reduction strategy for assembling the full-order residual and Jacobian, and a lower dimensionality of the projection subspaces for a given accuracy. The approach is robust, and features convergence rates that are analogous to those of classical reduced basis algorithms. The method was recently included in [GridapROM.jl](https://github.com/gridap/GridapROMs.jl).

$$ 
\begin{table}[t]
    \small
    \begin{tabular}{cccccccc} 
        \toprule

        & &\multicolumn{3}{c}{\textbf{2-}$\bm{d}$} &\multicolumn{3}{c}{\textbf{3-}$\bm{d}$} \\

        \cmidrule(lr){3-5} \cmidrule(lr){6-8}
    
        &\multicolumn{1}{c}{\textbf{Measure}}
        &\multicolumn{1}{c}{$\bm{h} = 1/250$}
        &\multicolumn{1}{c}{$\bm{h} = 1/350$} 
        &\multicolumn{1}{c}{$\bm{h} = 1/460$} 
        &\multicolumn{1}{c}{$\bm{h} = 1/40$}
        &\multicolumn{1}{c}{$\bm{h} = 1/50$} 
        &\multicolumn{1}{c}{$\bm{h} = 1/60$}\\
        
        \midrule
    
        \multirow{2}{*}[0.1cm]{\textbf{POD}}
        &\textbf{WT} $(\si{\second})$ &$0.85$ &$2.13$ &$3.22$ &$5.74$ &$13.34$ &$30.31$ \\

        &\textbf{MEM} $(Gb)$ &$0.30$ &$0.63$ &$1.00$ &$2.24$ &$5.21$ &$10.29$ \\
    
        \midrule
    
        \multirow{2}{*}[0.1cm]{\textbf{TT-SVD}}
        &\textbf{WT} $(\si{\second})$ &$0.19$ &$0.32$ &$0.75$ &$0.18$ &$0.39$ &$0.69$ \\

        &\textbf{MEM} $(Gb)$ &$0.16$ &$0.29$ &$0.42$ &$0.11$ &$0.18$ &$0.28$ \\

        \bottomrule 
    \end{tabular}
    \caption{Offline results, Poisson equation. From left to right: results obtained on a 2D geometry, and a 3D geometry, for different mesh sizes $h$. From top to bottom: wall time (WT) and memory allocations (MEM) associated with the construction of the $H^1$-orthogonal basis, using the truncated POD and the tensor-train SVD, respectively. The results are computed considering the accuracy tolerance $\varepsilon = 10^{-4}$.}
    \label{tb: rb offline poisson equation}
\end{table}
$$

## Cutting-edge advancements in reduced order models for space-time problems 

I contributed towards the development of advanced reduced order models for the solutions of parameterized, unsteady partial differential equations. The main contributions are:

- The proposal of a novel discrete interpolation method for the joint approximation in space and time of finite element residuals and Jacobians. 
- The developemnt of stabilized reduced bases methods for the efficient solution of haemodynamics problems in arterial blocks. These methods greatly improve the efficiency of traditional reduced bases schemes in space only, while achieving the same accuracy .

$$
\begin{table}[t!]
	\centering
	
	% \begin{tabular}{c c c c c c c c c}
	% 	\toprule
	% 	& &
	% 	\multicolumn{3}{c}{\large\textbf{ROM size}}&
	% 	\multicolumn{2}{c}{\large\textbf{Efficiency}}&
	% 	\multicolumn{2}{c}{\large\textbf{Accuracy}}\\
		
	% 	\cmidrule(lr){3-5} \cmidrule(lr){6-7} \cmidrule(lr){8-9}
		
	% 	&
	% 	$\bm{\varepsilon}$ & 
	% 	\multicolumn{1}{c}{$\bm{(n_u^s,n_u^t)}$} & 
	% 	\multicolumn{1}{c}{$\bm{(n_p^s,n_p^t)}$} &
	% 	\multicolumn{1}{c}{$\bm{(\{N_{\lambda_k}\},\{n_{\lambda_k}^t\})}$} &
	% 	\multicolumn{1}{c}{\textbf{RF}} & 
	% 	\multicolumn{1}{c}{\textbf{SU}} & 
	% 	\multicolumn{1}{c}{$\bm{E_u / \varepsilon_u}$} & 
	% 	\multicolumn{1}{c}{$\bm{E_p / \varepsilon_p}$} \\
		
	% 	\midrule
		
	% 	\multirow{3}{*}{\rotatebox[origin=c]{90}{\textbf{\footnotesize SRB--TFO}}} & $\bm{10^{-3}}$ &(184,170) &(7,170) &(\{63,63\},\{170,170\}) &7.74e2 &2.11e3 &11.76 &2.40 \\
	% 	& $\bm{10^{-4}}$ &(220,170) &(14,170) &(\{63,63\},\{170,170\}) &6.81e2 &1.79e3 &14.59 &2.70  \\
	% 	& $\bm{10^{-5}}$ &(303,170) &(31,170) &(\{63,63\},\{170,170\}) &5.33e2 &1.55e3 &12.05 &8.13 \\
		
	% 	\midrule
		
	% 	\multirow{3}{*}{\rotatebox[origin=c]{90}{\textbf{\footnotesize ST--GRB}}} & $\bm{10^{-3}}$ &(184,$10^{*_3}$) &(7,9) &(\{63,63\},\{8,8\}) &1.43e4 &2.18e4 &12.74 &4.29 \\
	% 	& $\bm{10^{-4}}$ &(220,$12^{*_2}$) &(14,11) &(\{63,63\},\{11,11\}) &9.97e3 &8.19e4 &14.91 &3.17  \\
	% 	& $\bm{10^{-5}}$ &(303,$16^{*_4}$) &(31,14) &(\{63,63\},\{14,14\}) &5.92e3 &2.39e3 &10.02 &9.20 \\
		
	% 	\midrule
		
	% 	\multirow{3}{*}{\rotatebox[origin=c]{90}{\textbf{\footnotesize ST--PGRB \hspace{0.5cm}}}} & $\bm{10^{-3}}$ &(51,7) &(7,9) &(\{63,63\},\{8,8\}) &2.92e4 &1.17e5 &16.70 &8.22 \\
	% 	& &(51,$10^{*_3}$) &(7,9) &(\{63,63\},\{8,8\}) &2.64e4 &9.17e4 &12.28 &5.48 \\
	% 	& $\bm{10^{-4}}$ &(87,10) &(14,11) &(\{63,63\},\{11,11\}) &1.73e4 &3.19e4 &11.95 &11.27 \\
	% 	& &(87,$12^{*_2}$) &(14,11) &(\{63,63\},\{11,11\}) &1.61e3 &2.68e4 &9.71 &10.79  \\
	% 	& $\bm{10^{-5}}$ &(146,12) &(31,14) &(\{63,63\},\{14,14\}) &1.06e4 &9.00e3 &21.98 &19.34 \\
	% 	& &(146,$16^{*_4}$) &(31,14) &(\{63,63\},\{14,14\}) &9.19e3 &6.00e3 &13.45 &11.60 \\
	% 	\bottomrule 
	% \end{tabular}%
	% \caption{Summary of the results obtained with the ST--RB methods (top: ST--GRB, bottom: ST--PGRB) on the Femoropopliteal Bypass test case, for different POD tolerances $\varepsilon$. In particular: (left) number of spatial and temporal reduced basis elements for velocity, pressure and Lagrange multipliers; (center) RF and average SU; (right) normalized average test relative errors on velocity and pressure.}
	% \label{tab:bypass ST--RB}
	
	\includegraphics[width=0.475\textwidth]{assets/bypass_clot_ST-GRB.png}
	\hfill
	\includegraphics[width=0.475\textwidth]{assets/bypass_clot_ST-PGRB.png}
	\captionof{figure}{Magnitudes of the velocity, pressure and WSS fields (top) and corresponding absolute pointwise errors with respect to the FOM solution (bottom), achieved in the Femoropopliteal Bypass test case with the ST--GRB method (left) and ST--PGRB method (right) for $\varepsilon=10^{-3}$, at $t=0.1075$ \si{\second} (systolic peak) and with $\bm{\mu}^*=[0.130, 1.604, 15.025, 0.714, 0.57, 536, 846, 0, 23.3]$.}
	\label{fig:bypass_plots}	
\end{table}
$$