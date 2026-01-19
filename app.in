import streamlit as st

st.title("🤖 AI Based To-Do List")

st.write("Add your tasks and AI will help you organize them!")

tasks = st.text_area("Enter your tasks (one per line)")

if st.button("Analyze Tasks"):
    task_list = tasks.split("\n")

    st.subheader("📌 Your Tasks")
    for task in task_list:
        if "exam" in task.lower() or "study" in task.lower():
            st.write("⭐ Important:", task)
        else:
            st.write("✔ Normal:", task)

    st.subheader("🧠 AI Suggestion")
    st.write("Do important tasks first, then normal tasks.")
