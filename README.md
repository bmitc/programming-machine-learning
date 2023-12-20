**Update**: This project keeps getting put aside, and then me coming back to it. Lately, I am interested in actually completing the book, which is for obvious purposes, but using all three of Python, F#, and Elixir with their respective notebook solutions as a point of learning and comparison.

# Programming Machine Learning

F# implementations of the machine learning projects in the book [Programming Machine Learning: From Coding to Deep Learning](https://pragprog.com/titles/pplearn/programming-machine-learning/).

The book uses Python with the minimal dependencies of `numpy`, `matplotlib`, and `seaborn`. I initially tried to use [Numsharp](https://github.com/SciSharp/NumSharp) and [Numpy.NET](https://github.com/SciSharp/Numpy.NET), but neither one of these worked well. I eventually found it easier to just implement everything directly in F# myself, using [XPlot.Plotly](https://fslab.org/XPlot/) for the plots, rather than trying to shoehorn some Numpy solution in. The current intention is to implement everything in .NET Interactive notebooks using F#.

# To use the notebooks

1. Install [.NET 5 SDK](https://dotnet.microsoft.com/download/dotnet/5.0)
2. Install [Visual Studio Code](https://code.visualstudio.com/)
3. Install the [.NET Interactive Notebooks extension](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) in Visual Studio Code
4. Clone the repository. (As a note, GitHub does a simple render of the notebooks in the browser, so you can at least browse the basics of the notebooks in a browser. But you won't see everything, for example the plots.)
5. Open Visual Studio Code, use the keyboard shortcut `Ctrl+Shift+P` to open the command palette, type `open notebook`, and select `.NET Interactive: Open notebook` to open a notebook. You may need to update paths to data files, but this should be straightforward.
