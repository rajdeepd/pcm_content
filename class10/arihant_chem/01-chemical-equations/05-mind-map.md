---
layout: default
title: 1.5 Mind Map
nav_order: 5
parent: Chemical Reactions and Equations
grand_parent: Arihant Chemistry
mathjax: true
---

# 1.5 Mind Map

<svg width="1000" height="1200" viewBox="0 0 1000 1200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      text { font-family: Arial, sans-serif; }
      .title { font-size: 40px; font-weight: bold; fill: #d64cb6; font-style: italic; }
      .box-title { font-size: 14px; font-weight: bold; }
      .content { font-size: 11px; }
      .formula { font-family: 'Courier New', monospace; font-size: 10px; font-weight: bold;}
      .box-stroke { fill: white; stroke: #e08dcde0; stroke-width: 2; rx: 5; }
      .line-stroke { stroke: #e08dcd; stroke-width: 1; fill: none; }
      .sub { font-size: 8px; baseline-shift: sub; }
      .circle-node { fill: white; stroke: #a33e6b; stroke-width: 1; }
      .ball { fill: white; stroke: black; stroke-width: 1; }
    </style>
    <marker id="arrow" markerWidth="10" markerHeight="10" refX="9" refY="3" orient="auto" markerUnits="strokeWidth">
      <path d="M0,0 L0,6 L9,3 z" fill="#e08dcd" />
    </marker>
  </defs>

  <rect width="1000" height="1200" fill="white" />

  <!-- Title and decorative elements -->
  <text x="250" y="60" class="title">Mind Map</text>
  <path d="M220,70 Q200,70 200,40 Q200,10 230,10 Q260,10 260,40 Q260,70 240,70 L240,80 L220,80 Z" fill="none" stroke="#d64cb6" stroke-width="3" />
  <line x1="225" y1="85" x2="235" y2="85" stroke="#d64cb6" stroke-width="2" />

  <!-- All connecting lines drawn first (behind boxes) -->
  <line x1="490" y1="380" x2="490" y2="530" class="line-stroke" />
  <line x1="350" y1="350" x2="170" y2="350" class="line-stroke" />
  <line x1="170" y1="350" x2="170" y2="250" class="line-stroke" />
  <line x1="630" y1="350" x2="620" y2="440" class="line-stroke" />
  <line x1="490" y1="320" x2="490" y2="310" class="line-stroke" />
  <line x1="630" y1="350" x2="790" y2="270" class="line-stroke" />
  <line x1="440" y1="580" x2="310" y2="500" class="line-stroke" />
  <line x1="450" y1="610" x2="170" y2="620" class="line-stroke" />
  <line x1="490" y1="630" x2="490" y2="690" class="line-stroke" />
  <line x1="540" y1="600" x2="640" y2="780" class="line-stroke" />
  <line x1="540" y1="580" x2="640" y2="640" class="line-stroke" />
  <line x1="530" y1="560" x2="640" y2="450" class="line-stroke" />

  <!-- All boxes and content drawn on top -->
  <rect x="350" y="320" width="280" height="60" class="box-stroke" stroke="#660033" />
  <text x="490" y="345" text-anchor="middle" font-size="18" font-weight="bold">CHEMICAL REACTIONS</text>
  <text x="490" y="365" text-anchor="middle" font-size="18" font-weight="bold">AND EQUATIONS</text>

  <circle cx="490" cy="580" r="50" class="box-stroke" />
  <text x="490" y="570" text-anchor="middle" font-weight="bold" font-size="12">Types of</text>
  <text x="490" y="585" text-anchor="middle" font-weight="bold" font-size="12">Chemical</text>
  <text x="490" y="600" text-anchor="middle" font-weight="bold" font-size="12">Reactions</text>

  <rect x="50" y="160" width="240" height="90" class="box-stroke" />
  <text x="60" y="180" class="box-title">Balanced Chemical Equations</text>
  <text x="60" y="195" class="content">The reactions in which the total number of</text>
  <text x="60" y="210" class="content">atoms of each element are equal on both</text>
  <text x="60" y="225" class="content">sides of the equation are called balanced</text>
  <text x="60" y="240" class="content">chemical equations.</text>

  <rect x="50" y="280" width="240" height="120" class="box-stroke" />
  <text x="60" y="300" class="box-title">Chemical Equations</text>
  <text x="60" y="315" class="content">It is the symbolic representation of a chemical</text>
  <text x="60" y="330" class="content">reaction, with the help of symbols and</text>
  <text x="60" y="345" class="content">formulae of the substance involved.</text>
  <text x="60" y="360" class="content">Reactants on left, products on right,</text>
  <text x="60" y="375" class="content">separated by an arrow.</text>

  <rect x="50" y="430" width="260" height="130" class="box-stroke" />
  <text x="60" y="450" class="box-title">1. Combination Reactions</text>
  <text x="60" y="465" class="content">Two or more reactants react together</text>
  <text x="60" y="480" class="content">to give a single product.</text>
  <g transform="translate(100, 495)">
      <circle cx="0" cy="0" r="8" class="ball"/><text x="-3" y="3" font-size="8">A</text>
      <text x="12" y="3">+</text>
      <circle cx="25" cy="0" r="8" class="ball"/><text x="22" y="3" font-size="8">B</text>
      <line x1="38" y1="0" x2="58" y2="0" stroke="black" marker-end="url(#arrow)" />
      <circle cx="70" cy="0" r="8" class="ball"/><text x="67" y="3" font-size="8">A</text>
      <circle cx="80" cy="0" r="8" class="ball"/><text x="77" y="3" font-size="8">B</text>
  </g>
  <text x="60" y="520" class="content">Burning of coal is an example.</text>
  <text x="60" y="535" class="formula">C(s) + O<tspan class="sub">2</tspan>(g) &#8594; CO<tspan class="sub">2</tspan>(g)</text>

  <rect x="50" y="580" width="260" height="320" class="box-stroke" />
  <text x="60" y="600" class="box-title">2. Decomposition Reactions</text>
  <text x="60" y="615" class="content">A single reactant breaks down into</text>
  <text x="60" y="630" class="content">two or more simpler products.</text>
  <g transform="translate(100, 645)">
      <circle cx="0" cy="0" r="8" class="ball"/><text x="-3" y="3" font-size="8">A</text>
      <circle cx="10" cy="0" r="8" class="ball"/><text x="7" y="3" font-size="8">B</text>
      <line x1="25" y1="0" x2="45" y2="0" stroke="black" marker-end="url(#arrow)" />
      <circle cx="60" cy="0" r="8" class="ball"/><text x="57" y="3" font-size="8">A</text>
      <text x="72" y="3">+</text>
      <circle cx="85" cy="0" r="8" class="ball"/><text x="82" y="3" font-size="8">B</text>
  </g>
  <text x="60" y="670" class="box-title" font-size="12">Thermal Decomposition</text>
  <text x="60" y="685" class="content">Heat is used to decompose substance.</text>
  <text x="60" y="700" class="content">Heating of zinc carbonate.</text>
  <text x="60" y="715" class="formula">ZnCO<tspan class="sub">3</tspan>(s) &#8594; ZnO(s) + CO<tspan class="sub">2</tspan>(g)</text>
  
  <text x="60" y="740" class="box-title" font-size="12">Electrolysis</text>
  <text x="60" y="755" class="content">Electricity is used to decompose.</text>
  <text x="60" y="770" class="content">Electrolysis of water.</text>
  <text x="60" y="785" class="formula">2H<tspan class="sub">2</tspan>O(l) &#8594; 2H<tspan class="sub">2</tspan>(g) + O<tspan class="sub">2</tspan>(g)</text>

  <text x="60" y="810" class="box-title" font-size="12">Photolysis</text>
  <text x="60" y="825" class="content">Substance is decomposed by using</text>
  <text x="60" y="840" class="content">light energy.</text>

  <rect x="330" y="160" width="280" height="150" class="box-stroke" />
  <text x="340" y="180" class="box-title">Steps Involved in Balancing a Chemical</text>
  <text x="340" y="195" class="box-title">Equation by Hit and Trial Method</text>
  <text x="340" y="215" class="content">Step I: Write unbalanced equation in brackets.</text>
  <text x="340" y="235" class="content">Step II: List elements in unbalanced eq.</text>
  <text x="340" y="255" class="content">Step III: Balance elements successively.</text>
  <text x="340" y="275" class="content">Step IV: Check correctness (atom count).</text>
  
  <rect x="360" y="390" width="260" height="100" class="box-stroke" />
  <text x="370" y="410" class="box-title">Characteristics of Chemical Reaction</text>
  <text x="370" y="430" class="content">• Change in state, colour</text>
  <text x="370" y="445" class="content">• Evolution of gas</text>
  <text x="370" y="460" class="content">• Change in temperature</text>
  <text x="370" y="475" class="content">• Formation of a precipitate</text>

  <rect x="340" y="690" width="260" height="210" class="box-stroke" />
  <text x="350" y="710" class="box-title">3. Exothermic Reactions</text>
  <text x="350" y="725" class="content">Reactions accompanied by evolution of heat.</text>
  <text x="350" y="740" class="formula">C<tspan class="sub">6</tspan>H<tspan class="sub">12</tspan>O<tspan class="sub">6</tspan> + 6O<tspan class="sub">2</tspan> &#8594; 6CO<tspan class="sub">2</tspan> + 6H<tspan class="sub">2</tspan>O + Energy</text>
  
  <text x="350" y="770" class="box-title">Endothermic Reactions</text>
  <text x="350" y="785" class="content">Reaction taking place by absorption of heat.</text>
  <text x="350" y="800" class="content">e.g. Photosynthesis</text>
  <text x="350" y="815" class="formula">6CO<tspan class="sub">2</tspan> + 12H<tspan class="sub">2</tspan>O &#8594; C<tspan class="sub">6</tspan>H<tspan class="sub">12</tspan>O<tspan class="sub">6</tspan> + 6O<tspan class="sub">2</tspan> + 6H<tspan class="sub">2</tspan>O</text>

  <rect x="640" y="60" width="310" height="210" class="box-stroke" />
  <text x="650" y="80" class="box-title">Effects of Oxidation Reactions in</text>
  <text x="650" y="95" class="box-title">Everyday Life</text>
  <text x="650" y="115" class="box-title" font-size="12">• Corrosion</text>
  <text x="650" y="130" class="content">Deterioration of metal by air, water, chemical.</text>
  <text x="650" y="145" class="content">Prevented by painting, galvanising.</text>
  <text x="650" y="165" class="box-title" font-size="12">• Rancidity</text>
  <text x="650" y="180" class="content">Slow oxidation of oil and fats in food.</text>
  <text x="650" y="195" class="content">Prevented by:</text>
  <text x="650" y="210" class="content">- Air tight containers</text>
  <text x="650" y="225" class="content">- Refrigeration</text>
  <text x="650" y="240" class="content">- Adding antioxidants</text>

  <rect x="640" y="280" width="310" height="290" class="box-stroke" />
  <text x="650" y="300" class="box-title">6. Oxidation and Reduction Reactions</text>
  <text x="650" y="315" class="content">Oxidation: Addition of O2 or removal of H2.</text>
  <text x="650" y="330" class="content">Reduction: Removal of O2 or addition of H2.</text>
  <text x="650" y="350" class="box-title" font-size="12">Redox Reactions</text>
  <text x="650" y="365" class="content">Oxidation and reduction occur simultaneously.</text>
  
  <text x="680" y="390" class="formula">CuO + H<tspan class="sub">2</tspan> &#8594; Cu + H<tspan class="sub">2</tspan>O</text>
  <path d="M690,385 Q710,365 730,385" fill="none" stroke="black" width="1"/>
  <text x="700" y="375" font-size="9">Reduction</text>
  <path d="M730,395 Q750,415 770,395" fill="none" stroke="black" width="1"/>
  <text x="740" y="410" font-size="9">Oxidation</text>

  <text x="650" y="430" class="box-title" font-size="12">Oxidising Agent or Oxidant</text>
  <text x="650" y="445" class="content">Substance causing oxidation of others.</text>
  <text x="650" y="465" class="box-title" font-size="12">Reducing Agent or Reductant</text>
  <text x="650" y="480" class="content">Substance causing reduction of others.</text>

  <rect x="640" y="580" width="310" height="120" class="box-stroke" />
  <text x="650" y="600" class="box-title">5. Double Displacement Reaction</text>
  <text x="650" y="615" class="content">In this reaction:</text>
  <g transform="translate(690, 630)">
     <circle cx="0" cy="0" r="7" class="ball"/><text x="-3" y="3" font-size="7">A</text>
     <circle cx="10" cy="0" r="7" class="ball"/><text x="7" y="3" font-size="7">B</text>
     <text x="20" y="3">+</text>
     <circle cx="30" cy="0" r="7" class="ball"/><text x="27" y="3" font-size="7">C</text>
     <circle cx="40" cy="0" r="7" class="ball"/><text x="37" y="3" font-size="7">D</text>
     <line x1="52" y1="0" x2="67" y2="0" stroke="black" marker-end="url(#arrow)" />
     <circle cx="75" cy="0" r="7" class="ball"/><text x="72" y="3" font-size="7">A</text>
     <circle cx="85" cy="0" r="7" class="ball"/><text x="82" y="3" font-size="7">D</text>
     <text x="95" y="3">+</text>
     <circle cx="105" cy="0" r="7" class="ball"/><text x="102" y="3" font-size="7">C</text>
     <circle cx="115" cy="0" r="7" class="ball"/><text x="112" y="3" font-size="7">B</text>
  </g>
  <text x="650" y="660" class="formula">Na<tspan class="sub">2</tspan>SO<tspan class="sub">4</tspan> + BaCl<tspan class="sub">2</tspan> &#8594; BaSO<tspan class="sub">4</tspan> + 2NaCl</text>

  <rect x="640" y="710" width="310" height="150" class="box-stroke" />
  <text x="650" y="730" class="box-title">4. Displacement Reactions</text>
  <text x="650" y="745" class="content">One element displaces the other from</text>
  <text x="650" y="760" class="content">its compound.</text>
  <g transform="translate(690, 780)">
     <circle cx="0" cy="0" r="7" class="ball"/><text x="-3" y="3" font-size="7">A</text>
     <text x="10" y="3">+</text>
     <circle cx="20" cy="0" r="7" class="ball"/><text x="17" y="3" font-size="7">B</text><circle cx="30" cy="0" r="7" class="ball"/><text x="27" y="3" font-size="7">C</text>
     <line x1="40" y1="0" x2="55" y2="0" stroke="black" marker-end="url(#arrow)" />
     <circle cx="65" cy="0" r="7" class="ball"/><text x="62" y="3" font-size="7">A</text><circle cx="75" cy="0" r="7" class="ball"/><text x="72" y="3" font-size="7">C</text>
     <text x="85" y="3">+</text>
     <circle cx="95" cy="0" r="7" class="ball"/><text x="92" y="3" font-size="7">B</text>
  </g>
  <text x="650" y="810" class="content">Also called single displacement.</text>
  <text x="650" y="830" class="formula">Fe + CuSO<tspan class="sub">4</tspan> &#8594; FeSO<tspan class="sub">4</tspan> + Cu</text>

</svg>
