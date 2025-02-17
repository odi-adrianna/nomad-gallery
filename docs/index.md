# Welcome to the `nomad-gallery`

A mkdocs-based GitHub Pages site for showcasing NOMAD features, examples, and use cases.

## Special Highlights

<!-- # Include a single card manually -->
{{ render_card_from_file("special_cards/Alexandria.md") }}

## Gallery

<!-- # Find all cards in cards/ and sort by date (newest first) -->
{{ render_sorted_cards() }}
