import streamlit as st

# Initialize counter in session state if not already present
if 'counter' not in st.session_state:
    st.session_state.counter = 0

# Function to increment the counter
def increment_counter():
    st.session_state.counter += 1

# Display the current counter value
st.write(f"Click Count: {st.session_state.counter}")

# Button to trigger increment
if st.button('Click Me!'):
    increment_counter()
