# ChessWithBinaryTrees

## Purpose
### The purpose of this project is to:
1. Cement the idea basic application design by creating a simple Chess game
1. Learn the effective ways of managing and creating BinaryTrees for data storage and effective traversal
to get desired results and
1. Creating effective ways of project management and phase developements

## Phases
### There will be **Five Phases** of the project:
1. Creation of the Chess Application
1. Creation of the BinaryTree assortment
1. Creation of the algorithm to train the AI
1. Training the AI
1. Intensive testing and optimization of the AI and code 

## Phase 1: Chess Application
### This phase consists of creating the Chess Game, do not focus on any other aspects other than recreating Chess
1. Create the Chess Pieces
	- Has the attribute of PlayerSide, defined by boolean: true meaning White, false meaning Black
	- Has the attribute of an enumerated value of ChessPieceType
		- Enumerations will be defined by: Pawn, Knight, Bishop, Rook, Queen and King
	- ChessPiece will have a constructor that takes the paramaters Bool PlayerSide and ChessPieceType PieceType
	- Add GetPlayerSide() and SetPlayerSide(Bool side) methods
	- Add GetPieceType() and SetPieceType(ChessPieceType pieceType)