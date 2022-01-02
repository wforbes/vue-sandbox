<template>
	<v-container>
		<v-row>
			<v-col>
				<h1>Home</h1>
				<AuthCard />
			</v-col>
		</v-row>
	</v-container>
</template>
<script>
import AuthCard from "@/home/components/AuthCard";
export default {
	name: "HomePage",
	components: {
		AuthCard
	},
	data() {
		return {};
	}
};
</script>
