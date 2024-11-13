# Does not allign with question
# Instead of searching for a file extension

file_name = input("File name: ").strip().lower()

# Dictionary to map extensions to media types
media_types = {
    ".gif": "image/gif",
    ".jpg": "image/jpeg",
    ".jpeg": "image/jpeg",
    ".png": "image/png",
    ".pdf": "application/pdf",
    ".txt": "text/plain",
    ".zip": "application/zip"
}

# Look up the media type in the dictionary, defaulting to "unknown type" if not found
for ext, media_type in media_types.items():
    if file_name.endswith(ext):
        print(media_type)
        break
else:
    print("unknown type")
