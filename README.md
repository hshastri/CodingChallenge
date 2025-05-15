# CodingChallenge

Package Sorter
This is a simple utility function designed for Thoughtful's robotic automation system to classify packages into appropriate stacks based on their volume, dimensions, and mass.

Classification Rules
Each package is sorted into one of three categories:

STANDARD: Not bulky and not heavy.

SPECIAL: Bulky or heavy (but not both).

REJECTED: Both bulky and heavy.

Definitions
Bulky: Volume ≥ 1,000,000 cm³ or any dimension ≥ 150 cm

Heavy: Mass ≥ 20 kg
