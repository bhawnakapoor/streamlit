# Streamlit Operations Reference Guide

A comprehensive reference application demonstrating all Streamlit features and operations for development teams.

## Overview

This repository contains a well-documented Streamlit application that serves as a reference for all common Streamlit operations and features. It's designed to help team members quickly understand and implement Streamlit functionality in their own projects.

## Features

The application demonstrates the following Streamlit features:

- **Authentication System**: User login with role-based access control
- **Custom Styling**: Theming and CSS customization
- **Sidebar Components**: Interactive controls with real-time updates
- **Data Visualization**: Examples using matplotlib, plotly, and st.map
- **Layout Components**: Tabs, expanders, and columns for better organization
- **Input Widgets**: All common input types with examples
- **Form Handling**: Complete form submission workflow
- **File Operations**: Upload and download functionality
- **Date and Time Components**: Date inputs with filtering examples
- **Session State Management**: Persistence between reruns
- **Caching**: Performance optimization with st.cache_data
- **Progress Indicators**: Visual feedback for operations
- **Component Embedding**: HTML and iframe integration
- **Admin Panel**: Role-based administrative interface

## Getting Started

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-org/streamlit-reference.git
   cd streamlit-reference
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```
   streamlit run streamlit_application.py
   ```

### Default Credentials

The application comes with pre-configured users:
- Admin: username `admin`, password `admin`
- Regular user: username `user`, password `user`

## Project Structure

- `streamlit_application.py`: The main application file
- `streamlit_operations.ipynb`: Jupyter notebook explaining all operations with examples
- `data.csv`: Sample data for demonstrations (generated if not present)
- `streamlit_users.json`: User credentials storage (created on first run)
- `requirements.txt`: Dependencies list

## Using the Reference

When implementing Streamlit features in your projects, follow these steps:

1. Run the reference application to see the feature in action
2. Locate the relevant section in the code
3. Copy and adapt the code for your own application

The code is extensively commented and organized into logical sections, making it easy to find and understand specific features.

## Component Quick Reference

### Basic Components
- Text: `st.title()`, `st.header()`, `st.markdown()`, `st.write()`
- Data: `st.dataframe()`, `st.table()`, `st.json()`

### Input Widgets
- Text: `st.text_input()`, `st.text_area()`, `st.number_input()`
- Selection: `st.checkbox()`, `st.radio()`, `st.selectbox()`, `st.multiselect()`
- Buttons: `st.button()`, `st.download_button()`
- Date/Time: `st.date_input()`, `st.time_input()`
- Other: `st.slider()`, `st.file_uploader()`, `st.color_picker()`

### Layout
- `st.columns()`: Create columns for side-by-side content
- `st.tabs()`: Create tabbed interfaces
- `st.expander()`: Collapsible content sections
- `st.sidebar`: Add controls to the sidebar

### Advanced Features
- `st.form()`: Group inputs with a submit button
- `st.session_state`: Persist values between reruns
- `st.cache_data`: Cache function results for performance
- `st.set_page_config()`: Configure page settings



