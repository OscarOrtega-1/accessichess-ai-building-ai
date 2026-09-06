# AccessiChess AI

**Final project for the Building AI course**

## Summary

AccessiChess AI is a voice-first and screen-reader-accessible chess system designed for blind and low-vision players. It combines accessible interaction, chess reasoning, natural language processing, and AI-assisted training to make playing and learning chess more independent and inclusive.

## Background

Chess software is widely available, but many digital chess interfaces depend heavily on visual boards, drag-and-drop controls, graphical coordinates, and interfaces that can be difficult to navigate with screen readers.

This creates several problems:

- Blind players may need additional assistance to understand the board position.
- Many chess applications are not fully compatible with screen readers.
- Navigating a complete chessboard through accessibility software can be slow.
- Visual indicators such as legal moves, threats, captures, and check warnings may not be announced clearly.
- Learning chess concepts often depends on diagrams and visual explanations.

The goal of AccessiChess AI is to make chess playable and understandable without requiring visual interaction.

The project is important because accessible design should allow people with disabilities to use technology independently rather than requiring them to adapt to interfaces designed primarily for sighted users.

## How is it used?

The user can interact with AccessiChess AI using a screen reader, keyboard commands, or voice.

For example, a player could say:

> Move knight from g1 to f3.

The system would verify whether the move is legal, update the board, and provide an accessible confirmation.

A player could also ask:

- What pieces are attacking my king?
- Describe the board.
- What is my opponent threatening?
- Suggest a good move and explain why.

The system would provide concise spoken or screen-reader-compatible responses.

Different description modes could be offered:

- Complete board description
- Changed pieces only
- Threats and captures
- Legal moves for a selected piece
- Tactical explanation
- Beginner teaching mode

The primary users would be blind and low-vision chess players, although the voice and educational functions could also be useful for other players.

Accessibility should be treated as a core system requirement rather than an additional feature.

## Data sources and AI methods

The project could use several kinds of data:

- Publicly available chess games
- Legal chess positions and move histories
- Chess engine evaluations
- User interaction data collected only with informed consent
- Accessibility testing feedback
- Synthetic chess positions generated for training and testing

Possible AI methods include:

### Natural language processing

NLP can translate spoken or written commands into structured chess actions and convert chess positions into understandable natural-language descriptions.

### Speech recognition and text-to-speech

Speech recognition can allow players to make moves and ask questions by voice. Text-to-speech can provide immediate accessible feedback.

### Search and optimization

Chess engines use search algorithms to evaluate possible moves and positions. These methods can help suggest strong moves and identify threats.

### Machine learning

Machine-learning models could adapt explanations to the player's skill level and identify which kinds of mistakes a player makes most frequently.

### Recommendation systems

The system could recommend exercises, openings, tactics, or lessons based on the user's previous games and learning progress.

AI-generated recommendations should never prevent the player from choosing their own move.

## Challenges

AccessiChess AI would not solve every accessibility problem automatically.

Important limitations include:

- Speech recognition can misunderstand chess coordinates or piece names.
- AI-generated explanations can be inaccurate.
- Users have different accessibility preferences.
- Chess engines may recommend strong moves without producing understandable explanations.
- Response latency must remain low during a game.
- Accessibility must be tested with real screen readers and real users.
- Personal data and game histories must be protected.
- Voice data should not be stored unless necessary and explicitly authorized.

The system should clearly distinguish between verified chess rules and AI-generated explanations.

A human-centered design process involving blind and low-vision users would be essential.

## What next?

The project could begin with a small accessible web prototype supporting:

1. Keyboard navigation
2. Screen-reader-compatible board representation
3. Legal move validation
4. Spoken board descriptions
5. Voice commands

Future versions could add:

- Personalized AI coaching
- Tactical training
- Multiplayer games
- Tournament accessibility
- Braille display support
- Mobile applications
- Multilingual voice interaction
- Accessible game analysis
- Integration with online chess platforms

A later research phase could compare different methods for describing complex chess positions efficiently to blind players.

The long-term goal would be an open and accessible chess platform where a player can independently play, study, analyze, and compete.

## Acknowledgments

This project was developed as the final project for the Building AI course by the University of Helsinki and Reaktor.

The concept is inspired by accessibility principles, inclusive design, chess software, screen-reader technologies, and research into artificial intelligence.

Possible future development may use open-source libraries and chess engines. Any external code, datasets, images, or documentation would be used only according to their respective licenses and would be properly credited.

No proprietary code or copyrighted material is included in this project proposal.
