package com.randomabc123.randomizer

import android.support.v7.app.AppCompactActivity
import android.os.Bundle
import android.widget.Button
import android.widget.SeekBar
import android.widget.TextView
import java.util.*

class MainActivity : AppCompactActivity() {
  override fun onCreate( savedInstanceState ? Bundle ) {
      super.onCreate( savedInstanceState )
      setContentView(R.layout.activity_main)

      val rollButton = findViewById<Button>(R.id.rollButton)
      val results = findViewById<TextView>(R.id.results)
      val seekBar = findViewById<SeekBar>(R.id.seekBar)

      rollButton.setOnClickListener {
          val randNum = Random().nextInt(seekBar.progress) + 1
          results.text = randNum.toString()
      }
  }
}
