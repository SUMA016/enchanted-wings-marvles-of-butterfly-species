marvelous_butterflies = [
    {"name": "Blue Morpho", "region": "South America", "wingspan_cm": 15, "feature": "Iridescent blue wings"},
    {"name": "Glasswing Butterfly", "region": "Central America", "wingspan_cm": 6, "feature": "Transparent wings"},
    {"name": "Ulysses Butterfly", "region": "Australia", "wingspan_cm": 14, "feature": "Bright blue color"},
    {"name": "Queen Alexandra's Birdwing", "region": "Papua New Guinea", "wingspan_cm": 28, "feature": "World's largest butterfly"},
]

for butterfly in marvelous_butterflies:
    print(f"Name: {butterfly['name']}")
    print(f"Region: {butterfly['region']}")
    print(f"Wingspan: {butterfly['wingspan_cm']} cm")
    print(f"Notable Feature: {butterfly['feature']}\n")