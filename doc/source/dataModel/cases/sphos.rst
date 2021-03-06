.. _sphos:

==============================================================================================
Open-shell, spherical-top molecules: sphos
============================================================================================== 


:math:`ElecStateLabel`
"""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""" 

:Element:   ``sphos:ElecStateLabel``  

:Attributes:   None. 

:Description:   ``ElecStateLabel`` is a label identifying the electronic state. 

:Restrictions:   * string.  


:math:`elecSym` 
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:elecSym``  

:Attributes:   ``group``: the symmetry group to which this species belongs.  

:Description:   ``elecSym`` is the symmetry species of the electronic wavefunction described by some symmetry group..  

:Restrictions:   * string.  


:math:`elecInv` 
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:elecInv``  

:Attributes:   None. 

:Description:   ``elecInv`` is the parity of the electronic wavefunction with respect to inversion through the molecular centre of mass in the molecular coordinate system..  

:Restrictions:   * 'g' or 'u'.  


:math:`S`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:S``  

:Attributes:   None.  

:Description:  :math:`S` is the quantum number associated with the total electronic spin angular momentum, :math:`\boldsymbol{S}`.  

:Restrictions:   * non-negative integer or half-odd integer.  


:math:`v_i` 
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:vi``  

:Attributes:   ``mode``: a positive integer, identifying the normal mode that this quantum number is associated with.  

:Description:   :math:`v_i` is the vibrational quantum number associated with the :math:`\nu_i` normal mode.  

:Restrictions:   * non-negative integer.  


:math:`l_i` 
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:li``  

:Attributes:   ``mode``: a positive integer, identifying the degenerate normal mode that this vibrational angular momentum quantum number is associated with.  

:Description:   :math:`l_i` is the vibrational angular momentum quantum number associated with the degenerate :math:`\nu_i` normal mode; positive and negative values distinguish :math:`l`\ -type doubling components.  

:Restrictions:   * non-negative integer.  * :math:`\|l_i\| = v_i, v_i-2, \cdots, 1 \;\mathrm{or}\;0`.  


:math:`vibSym`  
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:vibSym``  

:Attributes:   ``group``: the symmetry group to which this species belongs.  

:Description:   ``vibSym`` is the symmetry species of the vibrational wavefunction, in some appropriate symmetry group.  

:Restrictions:   * string.  


:math:`J`   
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:J``  

:Attributes:   None.  

:Description:  :math:`J` is the quantum number associated with the total angular momentum excluding nuclear spin, :math:`\boldsymbol{J}`.  

:Restrictions:   * non-negative integer or half-odd integer.  


:math:`N` 
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:N``  

:Attributes:   None.  

:Description:  :math:`N` is the quantum number associated with the total angular momentum excluding electronic and nuclear spin, N: :math:`\boldsymbol{J} = \boldsymbol{N} + \boldsymbol{S}`.  

:Restrictions:   * non-negative integer.  


:math:`rotSym`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:rotSym``  

:Attributes:   ``group``: the symmetry group to which this species belongs.  

:Description:   ``rotSym`` is the symmetry species of the rotational wavefunction, in some appropriate symmetry group.  

:Restrictions:   * string.  


:math:`I`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:I``  

:Attributes:  ``nuclearSpinRef``: a label identifying the group of nuclear spins coupled to one another to form a total nuclear spin angular momentum.  

:Description:  :math:`I` is the quantum number associated with the total nuclear spin angular momentum: :math:`\boldsymbol{I} = \boldsymbol{I_1} + \boldsymbol{I_2} + \cdots` where nuclei :math:`1, 2, \cdots` have individual nuclear spin angular momenta :math:`\boldsymbol{I_1}, \boldsymbol{I_2}, \cdots`.  

:Restrictions:   * non-negative integer or half-integer.  


:math:`F_j`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:Fj``  

:Attributes:   * ``nuclearSpinRef``: a label identifying the nuclear spin being coupled to   :math:`\boldsymbol{J}` or :math:`\boldsymbol{F_{j-1}}` to form an intermediate   angular momentum;  * :math:`j`: an integer label identifying the order of the hyperfine coupling  .  

:Description:   :math:`F_j` is the intermediate angular momentum quantum number associated with the coupling of the nuclear spin angular momentum of nucleus :math:`j` to the intermediate angular momentum: :math:`\boldsymbol{F_1} = \boldsymbol{J} + \boldsymbol{I_1}` or :math:`\boldsymbol{F_j} = \boldsymbol{F_{j-1}} + \boldsymbol{I_j}`; :math:`\boldsymbol{F_j}` is often not a good quantum number.  

:Restrictions:   * non-negative integer or half-integer.  


:math:`F`  
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:F``  

:Attributes:  ``nuclearSpinRef``: a label identifying the nuclear spin being coupled to :math:`\boldsymbol{J}` or :math:`\boldsymbol{F_j}` to form the total angular momentum.  

:Description:   :math:`F` is the quantum number associated with the total angular momentum including nuclear spin: :math:`\boldsymbol{F} = \boldsymbol{J} + \boldsymbol{I_1}` if only one such coupling is resolved, :math:`\boldsymbol{F} = \boldsymbol{F_{j-1}} + \boldsymbol{I_j}` if two or more such couplings are resolved.  

:Restrictions:   * non-negative integer or half-integer.  


:math:`r`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""   

:Element:   ``sphos:r``  

:Attributes:   ``name``: a string identifying this ranking index.  

:Description:   :math:`r` is a named, positive integer label identifying the state if no other good quantum numbers or symmetries are known.  

:Restrictions:   * positive integer.  


:math:`parity`
""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""""  

:Element:   ``sphos:parity``  

:Attributes:   None. 

:Description:   ``parity`` is the total parity: the parity of the total molecular wavefunction (excluding nuclear spin) with respect to inversion through the molecular centre of mass of all particles' coordinates in the laboratory coordinate system, the :math:`\hat{E}^*` operation.  

:Restrictions:   * ':math:`+`' or ':math:`-`'.  