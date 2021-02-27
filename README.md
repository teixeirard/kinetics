{ncpi_2S.func} 
	{ function for data fitting with ProFit 7.0.1, Quantum Soft, Uetikon am See, Switzerland, http://www.quansoft.com/}
	{Tilman Schirmer, Biozentrum, University of Basel}
	
	{non-competitive product inhibition (ncpi) with kinetic ligand binding       }
	{version for diguanylate cyclases, with two identical substrates      }
	
	
	
	{function used for Fig. 9 of Teixeira et al, 2021, Nat. Comm.: Activation mechanism of a small prototypic Rec-GGDEF diguanylate cyclase}
	
	
	{ 0a: EE+S <--> EES; assumption fast process ==> can be modeled with Kd) }
	{ 0b: EES + S <-> SEES}
	
	{ 1: SEES --kcat-> EE + P }
	
	{ 2a: EE + P <-> PEE}
	{ 2b: EES  + P <-> PEES}   {simplifiction, there should be two binding sites for P1, really}
	{ 2c: SEES + P <-> PSEES}   {simplification, there should be two binding sites for P1, really}
	
	{note: this is the nomenclature of the paper; below a slightly different nomenclature is used}
	{ E1 = EE : dimeric enzyme }
	{ E1S1 = EES }
	{ E1S1S1 = SEES}
	{ P1 = P}
	{ E1S1P1 = PEES}
	{ E1S1S1P1 = PSEES}
	
	{note: parameter sets associated with this function (to be set via Function>Parameter Sets) are: }
	{DgcR: native, wild-type DgcR}                     {Figs. 9b,c}
	{DgcR*: activated, wild-type DgcR}                 {Figs. 9b,c}
	{DgcR* (EDTA stopped): activated, wild-type DgcR}  {Fig. 9a}
	{DgcR_mut: native, inhib_mutant DgcR}              {Figs. 9b,c}
	{DgcR_mut*: activated, inhib_mutant DgcR}          {Figs. 9b,c}
	
	
	
	{ts/sk  23.7.2014}
	{14.5.2019}
	{ts 5.7.2020} {more annotations ts 27.2.2021}
