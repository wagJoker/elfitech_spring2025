
# SurveyCraft - Questionnaire Builder App

This project is a web-based application for creating, managing, and running questionnaires.

## Accomplished Level: Base Level

### Features implemented:

- **Questionnaire Catalog Page**
  - View a paginated list of questionnaires
  - Each card shows name, description, question count, and completion count
  - Actions: edit, run, and delete

- **Questionnaire Builder Page**
  - Create questionnaires with multiple questions
  - Supported question types: text, single choice, multiple choice
  - Save questionnaires to the database (localStorage)

- **Interactive Questionnaire Page**
  - Complete questionnaires created in the builder
  - View all answers and completion time at the end
  - Store responses in the database (localStorage)

## Technical Details

This project is built with:
- React
- TypeScript
- Tailwind CSS
- shadcn/ui components
- localStorage for data persistence

## Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm run dev
```

## Roadmap for Future Enhancements

- Middle Level: Implement sorting, drag and drop, and state preservation
- Advanced Level: Add infinite scroll, statistics pages, and image question type
