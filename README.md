# Ecommerce Command-Line Application

Welcome to the Grocery Store CLI App! 🛒 This is a down-to-earth Dart application that brings the joy of grocery shopping to your terminal. No flashy graphics here – just good old command-line charm.

## Quick Start

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/grocery-store-cli.git
   cd grocery-store-cli
   ```

2. **Run the Application:**
   ```bash
   dart bin/main.dart
   ```

## How It Works

### Options

- **View Items (v):** Check what's currently in your cart.
- **Add Item (a):** Add products to your cart by choosing from our list.
- **Checkout (c):** Complete your shopping and proceed to checkout.

### Structure

- **`main.dart`:** Your shopping guide. Handles user interaction and prompts.
- **`cart.dart`:** The Cart Manager. Keeps track of your selected items.
- **`item.dart`:** Meet the Products. Each product is an 'Item' with details.
- **`product.dart`:** Describes a Product. ID, name, and price – the essentials.

## Adding Products

Adding items is a breeze! Just type the letter next to the product you want (e.g., 'a' for apples), and voila! Your cart gets updated instantly.

## Checkout Experience

When you're ready to wrap up your virtual shopping spree, hit 'c'. We'll show you the total and ask for cash. We even calculate your change – just like a real cashier!

## Output Example

Let's run through a scenario:

1. **View Items:**
   ```
   What do you want to do? (v)iew items, (a)dd item, (c)heckout: v
   Cart is empty
   ```

2. **Add Item:**
   ```
   What do you want to do? (v)iew items, (a)dd item, (c)heckout: a
   Available products:
   (a)pples: $1.6
   (b)ananas: $0.7
   (c)ourgettes: $1.0
   (g)rapes: $2.0
   (m)ushrooms: $0.8
   (p)otatoes: $1.5
   Your choice: a
   ------
   1 x apples: $1.6
   Total: $1.6
   ------
   ```

3. **Checkout:**
   ```
   What do you want to do? (v)iew items, (a)dd item, (c)heckout: c
   Total: $1.6
   Payment in cash: 10
   Change: $8.40
   ```

Enjoy your virtual shopping experience! 🍎🛍️
