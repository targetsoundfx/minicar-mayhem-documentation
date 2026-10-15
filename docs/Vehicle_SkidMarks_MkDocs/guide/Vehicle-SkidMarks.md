# Vehicle: Skid Mark

## Overview

<div class="step">

<div class="step-text">

<h3>Overview</h3>

<p>
By default, the skid mark system is already set up on each vehicle.
</p>

<p>
Depending on the floor surface, the system instantiates a Line Renderer that represents the skid mark.
</p>

</div>

<div class="step-image">

</div>

</div>

## How to modify a skid mark

### Case 1: Modify all vehicles at once

If you want to modify only one vehicle, go to [Case 2](#case-2-modify-a-specific-vehicle).

In most cases, we want to modify the trails for all vehicles at once. To do this, modify the `CarRef` prefab in the Project folder:

`Assets → Prefabs → AS → Vehicle → Prefabs → Vehicle → CarRef`

<div class="step">

<div class="step-text">

<h3>1. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Open Trail List</h3>

<p>
For each surface, a trail prefab is associated.
</p>

</div>

<div class="step-image">

<img src="../images/trail-list.png" alt="Trail List containing the trail prefabs">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>4. Select the trail prefab</h3>

<p>
To access a trail prefab, click the prefab field (marked 1).
</p>

<p>
You can modify the skid mark prefab or replace it with another one.
</p>

</div>

<div class="step-image">

<img src="../images/trail-prefab-slot.png" alt="Trail prefab field highlighted in the Inspector">

</div>

</div>

### Case 2: Modify a specific vehicle

If you want to modify only one specific vehicle, follow these steps.

<div class="step">

<div class="step-text">

<h3>1. Select your vehicle prefab</h3>

<p>
Select your prefab in the Project tab.
</p>

</div>

<div class="step-image">

<img src="../images/carref-project-location.png" alt="Vehicle prefab in the Project window">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Select Vehicle_sc</h3>

<p>
In the Hierarchy, select <strong>Vehicle_sc</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/vehicle-sc-hierarchy.png" alt="Vehicle_sc selected in the Hierarchy">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>4. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>5. Open Trail List</h3>

<p>
For each surface, a trail prefab is associated.
</p>

</div>

<div class="step-image">

<img src="../images/trail-list.png" alt="Trail List containing the trail prefabs">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>6. Select the trail prefab</h3>

<p>
Click the prefab field (marked 1) to access the trail prefab. You can modify it or replace it with another one.
</p>

</div>

<div class="step-image">

<img src="../images/trail-prefab-slot.png" alt="Trail prefab field highlighted in the Inspector">

</div>

</div>

## How to disable the skid marks system

### Case 1: Modify all vehicles at once

If you want to modify only one vehicle, go to [Case 2](#case-2-modify-a-specific-vehicle-1).

To disable skid marks for all vehicles, modify the `CarRef` prefab in the Project folder:

`Assets → Prefabs → AS → Vehicle → Prefabs → Vehicle → CarRef`

<div class="step">

<div class="step-text">

<h3>1. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Disable skid marks</h3>

<p>
Uncheck <strong>Is Skidmark Allowed</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/skidmark-allowed-toggle.png" alt="Is Skidmark Allowed toggle highlighted">

</div>

</div>

### Case 2: Modify a specific vehicle

If you want to disable skid marks for only one specific vehicle, follow these steps.

<div class="step">

<div class="step-text">

<h3>1. Select your vehicle prefab</h3>

<p>
Select your prefab in the Project tab.
</p>

</div>

<div class="step-image">

<img src="../images/carref-project-location.png" alt="Vehicle prefab in the Project window">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Select Vehicle_sc</h3>

<p>
Select <strong>Vehicle_sc</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/vehicle-sc-hierarchy.png" alt="Vehicle_sc selected in the Hierarchy">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>4. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>5. Disable skid marks</h3>

<p>
Uncheck <strong>Is Skidmark Allowed</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/skidmark-allowed-toggle.png" alt="Is Skidmark Allowed toggle highlighted">

</div>

</div>

## How to disable skid marks on a specific surface

### Case 1: Modify all vehicles at once

If you want to modify only one vehicle, go to [Case 2](#case-2-modify-a-specific-vehicle-2).

To disable skid marks for a surface on all vehicles, modify the `CarRef` prefab in the Project folder:

`Assets → Prefabs → AS → Vehicles → Prefabs → Vehicle → CarRef`

<div class="step">

<div class="step-text">

<h3>1. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Select the surface</h3>

<p>
Select the surface you want to change in the list, then click the small circle (marked 1).
</p>

</div>

<div class="step-image">

<img src="../images/surface-object-picker-button.png" alt="Object picker button for a trail prefab">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>4. Choose None</h3>

<p>
A new window appears. Choose <strong>None</strong> in the list (marked 1).
</p>

</div>

<div class="step-image">

<img src="../images/object-picker-none.png" alt="None option in the object picker">

</div>

</div>

### Case 2: Modify a specific vehicle

If you want to disable skid marks on a surface for only one specific vehicle, follow these steps.

<div class="step">

<div class="step-text">

<h3>1. Select your vehicle prefab</h3>

<p>
Select your prefab in the Project tab.
</p>

</div>

<div class="step-image">

<img src="../images/carref-project-location.png" alt="Vehicle prefab in the Project window">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Open the prefab</h3>

<p>
In the Inspector, press the <strong>Open</strong> button to open the prefab.
</p>

</div>

<div class="step-image">

<img src="../images/prefab-open-button.png" alt="Open button in the prefab Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Select Vehicle_sc</h3>

<p>
Select <strong>Vehicle_sc</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/vehicle-sc-hierarchy.png" alt="Vehicle_sc selected in the Hierarchy">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>4. Find the Car Skidmark script</h3>

<p>
In the Inspector, go to the <strong>Car Skidmark</strong> script.
</p>

</div>

<div class="step-image">

<img src="../images/car-skidmark-inspector.png" alt="Car Skidmark component in the Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>5. Select the surface</h3>

<p>
Select the surface you want to change in the list, then click the small circle (marked 1).
</p>

</div>

<div class="step-image">

<img src="../images/surface-object-picker-button.png" alt="Object picker button for a trail prefab">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>6. Choose None</h3>

<p>
A new window appears. Choose <strong>None</strong> in the list (marked 1).
</p>

</div>

<div class="step-image">

<img src="../images/object-picker-none.png" alt="None option in the object picker">

</div>

</div>

## How to change the skid mark texture

<div class="step">

<div class="step-text">

<h3>1. Open the Skidmarks materials folder</h3>

<p>
In the Project tab, go to:
</p>

<p>
<code>Assets → Materials → Vehicle → Skidmarks</code>
</p>

</div>

<div class="step-image">

<img src="../images/skidmark-materials-folder.jpg" alt="Skidmarks materials folder in the Project window">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>2. Select the material</h3>

<p>
Select the material you want to change. For example, select <strong>Skidmark_Ice</strong>.
</p>

</div>

<div class="step-image">

<img src="../images/skidmark-ice-material.jpg" alt="Skidmark_Ice material selected">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>3. Replace the texture</h3>

<p>
In the Inspector, replace the texture with a new one (marked 1).
</p>

</div>

<div class="step-image">

<img src="../images/skidmark-material-texture.jpg" alt="Texture field highlighted in the material Inspector">

</div>

</div>

<div class="step">

<div class="step-text">

<h3>Tip</h3>

<p>
You can use the <strong>Skidmark02</strong> texture as a reference for your new texture.
</p>

<p>
<code>Assets → Textures → Vehicle → Skidmark02</code>
</p>

</div>

<div class="step-image">

</div>

</div>
