# Expo ImagePicker TypeError Bug

This repository demonstrates a bug in the Expo ImagePicker library where a `TypeError: undefined is not an object (evaluating 'response.data.uri')` error is thrown when selecting an image from the user's photo library.  The bug is caused by an incompatibility between older versions of the Expo SDK and ImagePicker library and certain image formats or metadata.

## Bug Reproduction

1. Clone this repository.
2. Install the dependencies: `npm install`
3. Run the app: `expo start`
4. Select an image from your photo library.
5. Observe the app crashing with the error message.

## Solution

The solution involves upgrading to the latest versions of Expo SDK and the ImagePicker library.  This typically resolves the URI handling issues that cause this error.  Additionally, error handling and null checks can prevent the crash if the upgrade isn't feasible.

## Contributing

Contributions are welcome!