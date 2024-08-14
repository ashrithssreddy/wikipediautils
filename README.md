
# Wikipedia Utils

**Wikipedia Utils** is a Python library designed to access and visualize metadata from the Media Wiki API. The primary purpose of this library is to graphically visualize the interconnectedness of Wikipedia pages and page categories, providing a high-level, 30,000-foot overview of any given subject matter.

## Features

- **Metadata Retrieval**: Seamlessly access and retrieve metadata from Wikipedia pages and categories using the Media Wiki API.
- **Graphical Visualization**: Generate visual representations of the interconnectedness of Wikipedia pages and their categories.
- **Flexible and Modular**: Use individual utilities or combine them for more complex analyses.
- **Ease of Use**: Designed to be user-friendly, with intuitive function names and parameters.

## Installation

You can install Wikipedia Utils using pip:

\`\`\`bash
pip install wikipediautils
\`\`\`

Alternatively, you can clone the repository and install it manually:

```bash
git clone https://github.com/ashrithssreddy/wikipediautils.git
cd wikipediautils
pip install -r requirements.txt
```

## Usage

Here’s a simple example to get you started:

\`\`\`python
from wikipediautils.api_access import get_page_metadata
from wikipediautils.visualization import visualize_interconnectedness

# Retrieve metadata for a Wikipedia page
metadata = get_page_metadata('Artificial_intelligence')

# Visualize the interconnectedness of the Wikipedia page and its categories
visualize_interconnectedness(metadata)
\`\`\`

### Example Output

![Sample Visualization](examples/sample_output.png)

The above visualization represents the interconnectedness of the Wikipedia page "Artificial Intelligence" with its categories.

## Documentation

Detailed documentation for each function and module is available [here](link-to-docs). 

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) to get started. You can contribute by reporting issues, suggesting features, or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Wikipedia community and contributors.
- The developers of the Media Wiki API.

## Contact

For any inquiries, please contact Ashrith Reddy at [ashrithssreddy@gmail.com].
