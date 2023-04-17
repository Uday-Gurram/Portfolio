<!DOCTYPE html>
<html>
<head>
	<title>Portfolio Landing Page</title>
	<style>
		/* Styles for Search Bar */
		.search-container {
			text-align: center;
			margin-top: 50px;
			margin-bottom: 50px;
		}
    .search-container input[type=text] {
		padding: 10px;
		border: none;
		width: 50%;
		font-size: 17px;
		background-color: #f1f1f1;
		border-radius: 25px;
		text-align: center;
	}

	.search-container button {
		background-color: #4CAF50;
		color: white;
		border-radius: 25px;
		cursor: pointer;
		padding: 10px 20px;
		margin-left: 10px;
		border: none;
	}

	/* Styles for Project Grid */
	.row {
		display: flex;
		flex-wrap: wrap;
		padding: 0 4px;
	}

	.column {
		flex: 33.33%;
		max-width: 33.33%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		vertical-align: middle;
		width: 100%;
		cursor: pointer;
	}

	@media screen and (max-width: 800px) {
		.column {
			flex: 50%;
			max-width: 50%;
		}
	}

	@media screen and (max-width: 600px) {
		.column {
			flex: 100%;
			max-width: 100%;
		}
	}
</style>   
</head>
<body>
  <!-- Search Bar Section -->
<div class="search-container">
	<input type="text" placeholder="Search Projects...">
	<button type="submit"><i class="fa fa-search"></i></button>
</div>

<!-- Project Grid Section -->
<div class="row">
	<div class="column">
		<a href="#">
			<img src="project1.jpg" alt="Project 1">
		</a>
	</div>
	<div class="column">
		<a href="#">
			<img src="project2.jpg" alt="Project 2">
		</a>
	</div>
	<div class="column">
		<a href="#">
			<img src="project3.jpg" alt="Project 3">
		</a>
	</div>
</div>

<!-- Duplicate Project Grid Section 2 -->
<div class="row">
	<div class="column">
		<a href="#">
			<img src="project4.jpg" alt="Project 4">
		</a>
	</div>
	<div class="column">
		<a href="#">
			<img src="project5.jpg" alt="Project 5">
		</a>
	</div>
	<div class="column">
		<a href="#">
			<img src="project6.jpg" alt="Project 6">
		</a>
	</div>
</div>

<!-- Duplicate Project Grid Section 3 -->
<div class="row">
	<div class="column">
		<a href="#">
			<img src="project7.jpg" alt="Project 7">
		</a>
	</div>
	<div class="column">
		<a href="#">
			<img src="project8.jpg" alt="Project 8">
		</a>
	</div>
	<div class="column">
	

        
