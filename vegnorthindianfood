import streamlit as st
import numpy as np

# Title
st.title("🍛 What Should I Cook Today? (Veg Edition)")

# Intro text
st.markdown("Feeling confused about what to make today? Let me pick a **random North Indian veg curry** for you!")

# List of 100 veg curries
veg_dishes = np.array([
    "Paneer Butter Masala", "Shahi Paneer", "Kadai Paneer", "Palak Paneer", "Matar Paneer",
    "Malai Kofta", "Aloo Gobi", "Aloo Matar", "Chana Masala", "Rajma",
    "Dal Makhani", "Dal Tadka", "Baingan Bharta", "Bhindi Masala", "Lauki Kofta",
    "Gatte ki Sabzi", "Kadhi Pakora", "Mixed Vegetable Curry", "Tinde ki Sabzi", "Arbi Masala",
    "Tamatar Paneer", "Kumbh Masala", "Methi Malai Matar", "Karela Besan", "Dhingri Matar",
    "Dum Aloo", "Kashmiri Dum Aloo", "Aloo Tamatar", "Baingan Aloo", "Methi Aloo",
    "Chole", "Kala Chana Curry", "Matar Mushroom", "Paneer Tikka Masala", "Veg Kolhapuri",
    "Veg Jalfrezi", "Navratan Korma", "Veg Korma", "Lauki Chana Dal", "Turai Chana Dal",
    "Moong Dal Tadka", "Chana Dal Fry", "Aloo Baingan", "Aloo Palak", "Palak Chole",
    "Methi Paneer", "Tamatar Bharta", "Bottle Gourd Curry", "Bharwa Bhindi", "Bharwa Karela",
    "Hariyali Paneer", "Tawa Paneer Masala", "Lasooni Palak", "Saag Aloo", "Amritsari Chole",
    "Pindi Chole", "Kabuli Chana Masala", "Soya Chaap Curry", "Soya Matar Curry", "Matar Nimona",
    "Baingan Masala", "Tamatar Bhindi", "Dahi Aloo", "Dahi Bhindi", "Aloo Rasedar",
    "Sev Tamatar ki Sabzi", "Mangodi ki Sabzi", "Besan ki Sabzi", "Patta Gobi Aloo", "Jackfruit Curry",
    "Paneer Bhurji", "Paneer Lababdar", "Khatti Meethi Lauki", "Hara Chana Masala", "Palak Corn",
    "Methi Malai Paneer", "Tinda Matar", "Cholia Curry", "Baingan Mirchi ka Salan", "Aloo Tamatar Jhol",
    "Khoya Paneer", "Chana Dal Lauki", "Nargisi Kofta", "Chole Paneer", "Matar Gobi",
    "Aloo Chole", "Chane ki Dal Tadka", "Mix Dal Fry", "Baingan Tamatar Curry", "Lauki Tamatar Curry",
    "Bhindi Do Pyaza", "Mushroom Do Pyaza", "Tinda Aloo", "Pumpkin Curry", "Palak Matar",
    "Hing Jeera Aloo", "Bathua Raita Curry", "Singhare Aloo Curry", "Paneer Pasanda", "Aloo Kofta Curry"
])

# Button to pick a random dish
if st.button("🎲 Suggest a Dish"):
    random_index = np.random.randint(0, len(veg_dishes))
    st.success(f"👉 You should try making: **{veg_dishes[random_index]}**")
else:
    st.info("Click the button above to get a random dish suggestion!")
