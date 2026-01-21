# Dart-Async-Await


void main() async {
  print("Line 1");
  print("Line 2");
  await ss();
  print("Line 4");
  print("Line 5");
  print("Line 6");
}

Future<void> ss() async {
  await Future.delayed(Duration(seconds: 3));
  print("Line 3");
}
