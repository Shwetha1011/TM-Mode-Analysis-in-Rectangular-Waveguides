# TM-Mode-Analysis-in-Rectangular-Waveguides

This MATLAB script calculates and visualizes the field patterns of a rectangular waveguide operating in a specific TM mode. The script allows for user input of mode values and provides plots of the electric and magnetic field distributions.

## Features

- Calculates the cutoff frequency and wavelength for the given waveguide dimensions and mode values.
- Checks if the selected mode exists and if it propagates at the given frequency.
- Plots the electric and magnetic field patterns for the specified TM mode.

## Parameters

- **Waveguide Dimensions:**
  - `a` = 2.286 cm (length in x-direction)
  - `b` = a/2 cm (length in y-direction)
- **Frequency of Operation:** `f` = 45 GHz
- **User Inputs:**
  - `m` = Mode value in x-direction
  - `n` = Mode value in y-direction

## How It Works

1. **Input Mode Values**: Enter the mode values `m` and `n` when prompted.
2. **Calculate Cutoff Frequency**: Computes the cutoff frequency `fc` for the given mode and waveguide dimensions.
3. **Field Pattern Calculation**: Calculates the propagation constants and field distributions.
4. **Plotting**:
   - **Electric Field (E-Field)**: Plots the front view of the electric field distribution.
   - **Magnetic Field (H-Field)**: Plots the front view of the magnetic field distribution.
   - **Combined View**: Overlays the electric and magnetic field plots for comparison.

## Sample Usage

1. Run the script in MATLAB.
2. Enter the desired mode values for `m` and `n` when prompted.
3. View the generated plots of the E-Field and H-Field.

## Example Input and Output

- **Input Mode Values:**
  - `m = 1`
  - `n = 1`

- **Output Plots:**
  - Electric Field (E-Field) plot
  - Magnetic Field (H-Field) plot
  - Combined E-Field and H-Field plot

## Notes

- Ensure the frequency of operation is higher than the cutoff frequency for the mode to propagate.
- Replace placeholder field expressions with actual field equations for accurate results.


