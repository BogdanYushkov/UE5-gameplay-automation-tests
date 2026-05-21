# Minigun Automation Test

This automated gameplay test validates the core mechanics of the **Minigun** ability.

The test verifies:

- Minigun activation
- Shooting simulation
- Damage application
- Minigun duration
- Stun immunity
- Crouch restriction during Minigun
- Final validation state

---

# Video of the Autotest

<p align="center">
  <img src="../../MediaFiles/Videos/Minigun.gif" width="1000"/>
</p>

---

# Full Blueprint Overview

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_0.jpg" width="1400"/>
</p>

Complete overview of the automation test Blueprint graph.

---

# 1. Test Character Initialization

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_1.jpg" width="1000"/>
</p>

The test initializes Primary and Secondary test characters after spawning.

### Main actions:
- Assign spawned heroes
- Store references for gameplay checks
- Prepare the test environment

---

# 2. Minigun State Tracking

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_2.jpg" width="1000"/>
</p>

Tracks the Minigun gameplay state and restores the initial test state when required.

### Checks:
- Ability activation state
- Gameplay tag tracking
- Correct state transitions

---

# 3. Crouch Restriction Validation

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_3.jpg" width="1000"/>
</p>

Verifies that the Bounty Hunter cannot crouch while Minigun is active.

### Checks:
- Crouch state detection
- Gameplay restriction validation
- Error logging if crouching becomes available

---

# 4. Stun Immunity Validation

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_4.jpg" width="1000"/>
</p>

Checks that the character remains immune to stun effects during active Minigun.

### Checks:
- Stun gameplay tag monitoring
- Immunity validation
- Error logging on stun application

---

# 5. Damage Logging

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_5.jpg" width="1000"/>
</p>

Tracks health attribute changes and logs damage dealt by Minigun bullets.

### Checks:
- Damage calculation
- Attribute monitoring
- Correct damage logging

---

# 6. Ability Activation and Shooting Simulation

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_6.jpg" width="1000"/>
</p>

Simulates player input to activate the Minigun ability and perform continuous shooting.

### Simulated actions:
- Ability activation key press
- Mouse input simulation
- Continuous firing duration

---

# 7. Minigun Duration Validation

<p align="center">
  <img src="../../MediaFiles/Screenshots/Minigun/Screenshot_7.jpg" width="1000"/>
</p>

Measures Minigun active duration and compares it with expected configuration values.

### Checks:
- Ability duration timing
- Config parameter validation
- Float comparison with tolerance
- Correct Minigun lifetime

---

# Skills Demonstrated

- Unreal Engine 5
- Gameplay automation testing
- Blueprint scripting
- Gameplay Ability System (GAS)
- Gameplay Tags
- Async attribute monitoring
- Runtime gameplay validation
- Input simulation testing

---

# Technologies Used

- Unreal Engine 5
- Blueprint Automation Testing
- Gameplay Ability System (GAS)
- Gameplay Tags
- Blueprint Async Tasks
- Event-driven gameplay validation

---

# Test Result

✅ Test passes only if all gameplay validation checks succeed.

---

# Author

Bogdan Yushkov  
QA Automation Engineer / Unreal Engine 5
