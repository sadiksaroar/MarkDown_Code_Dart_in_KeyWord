import 'package:markdown/markdown.dart' as markdown;

void main() {
  String mdText = """
  # Dart Basics: Keywords, Variables & Data Types
  
  Dart শেখার শুরুতে তোমাকে কিছু **মূল ধারণা** বুঝতে হবে, যেমন **কীওয়ার্ড, ভেরিয়েবল ও ডাটা টাইপ**। 🚀

  ## 🔹 1. Keywords in Dart  
  Dart-এ কিছু সংরক্ষিত (reserved) কীওয়ার্ড রয়েছে, যেগুলো ব্যবহার করা যায় না।

  ### ✅ Control Flow Keywords  
  `if`, `else`, `switch`, `case`, `for`, `while`, `do`, `break`, `continue`, `return`  

  ```dart
  var age = 25;  
  final country = "Bangladesh";  
  const pi = 3.1416;
