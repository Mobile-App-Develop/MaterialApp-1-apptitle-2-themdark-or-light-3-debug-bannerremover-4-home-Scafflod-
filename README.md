# MaterialApp-1-apptitle-2-themdark-or-light-3-debug-bannerremover-4-home-Scafflod-
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      theme: ThemeData(brightness: Brightness.light),
      darkTheme: ThemeData(brightness: Brightness.dark),
      themeMode: ThemeMode.system,
      debugShowCheckedModeBanner: false,
      home: Scaffold(
        appBar: AppBar(
          title: Center(child: Text("Khadim Hussain")),
        ),
        floatingActionButton: FloatingActionButton(
          child: Icon(Icons.add),
          onPressed: () {},
        ),
        backgroundColor: Colors.yellowAccent,
        drawer: Drawer(
          child: Text('myapp'),
        ),
      ),
    ),
  );
}
