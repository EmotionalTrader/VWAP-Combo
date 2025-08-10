# VWAP-Combo 
VWAP Combo: Weekly WVAP + Fibonacci levels and Daily WVAP + Standard Deviation levels 
This TradingView Pine Script combines two powerful VWAP (Volume Weighted Average Price) indicators with different timeframes and deviation methods:

- Daily VWAP with Standard Deviation Bands (Yellow line)

        - Ideal for short-term scalping strategies

        - Shows standard deviation levels around the daily VWAP

- Weekly VWAP with Fibonacci Extension Bands (Orange line)

        - Excellent for intraday to short swing trading

        - Features colored zones based on Fibonacci extensions



  Daily VWAP (Yellow) System

    Core Line: Yellow VWAP calculated on daily timeframe

    Deviation Bands:

        Gray lines at ±1.28 standard deviations (configurable)

        Colored lines at ±2.01 standard deviations (configurable)

    Previous Day VWAP: Optional plot showing yesterday's VWAP as dotted line

    Bar Coloring: Option to color bars based on position relative to VWAP



Weekly VWAP (Orange) System

    Core Line: Orange VWAP calculated on weekly timeframe

    Fibonacci Zones:

        Red zone above: 1.618-2.618 Fibonacci extensions of standard deviation

        Green zone below: 1.618-2.618 Fibonacci extensions of standard deviation

    Deviation Filter: Only shows zones when weekly standard deviation > threshold (default 150)

    Reversal Signals: Identifies potential reversal points at zone boundaries



🛠 Customization Options

Users can configure:

    Colors for all lines and zones

    Transparency levels for shaded areas

    Fibonacci extension values (default 1.618 and 2.618)

    Standard deviation multipliers

    Toggle visibility of either system

    Enable/disable bar coloring features



💡 Trading Applications

    Daily System: Best for mean-reversion strategies within the trading day

    Weekly System: Helps identify larger swing trade opportunities

    Combined they provide multi-timeframe context for better trade decisions



📈 How to Use

    Add to chart in TradingView

    Configure settings to match your trading style

    Look for:

        Price reactions at deviation bands

        Zone transitions between red/green areas

        Confluence between daily and weekly levels

Note: Works best on liquid assets with good volume profiles. I use it for ES and NQ but it also works good on commodoties like Gold, Oil etc.  
