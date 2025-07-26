main.dart


import 'package:flutter/material.dart';
import 'package:proj/WelcomeScreen.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      theme: ThemeData(
        scaffoldBackgroundColor: Color(0xFFF21325),
      ),
      home: WelcomeScreen(),
    );
  }
} 
