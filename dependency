class FormatTool:
    def clean_text(self, text: str) -> str:
        return text.strip().upper()

class DocumentPrinter:
    # Dependency: The printer temporarily uses the tool to do its job
    def print_doc(self, text: str, formatter: FormatTool):
        formatted_text = formatter.clean_text(text)
        print(f"Printing: {formatted_text}")
