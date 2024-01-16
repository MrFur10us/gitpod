<template>
	<div class="container">
		<HeaderBlock />
	</div>
	<div class="container2">
		<StartBlock />
		<TextBlock />
		<CodeBlock />
		<DesignBlock />
		<DevelopBlock />
		<SignBlock />
	</div>
	<div class="container3">
		<MoreBlock />
		<CopyBlock />
	</div>
	<div class="container">
		<TermBlock />
	</div>
</template>

<script>
import CodeBlock from "@/components/CodeBlock/CodeBlock.vue";
import DesignBlock from "@/components/DesignBlock/DesignBlock.vue";
import DevelopBlock from "@/components/DevelopBlock/DevelopBlock.vue";
import HeaderBlock from "@/components/HeaderBlock/HeaderBlock.vue";
import StartBlock from "@/components/StartBlock/StartBlock.vue";
import TextBlock from "@/components/TextBlock/TextBlock.vue";
import SignBlock from "@/components/SignBlock/SignBlock.vue";
import MoreBlock from "@/components/MoreBlock/MoreBlock.vue";
import CopyBlock from "@/components/CopyBlock/CopyBlock.vue";
import TermBlock from "@/components/TermBlock/TermBlock.vue";

export default {
	name: "HomePage",
	data() {
		return {
			isChecked: false,
		};
	},
	methods: {},
	components: { HeaderBlock, StartBlock, TextBlock, CodeBlock, DesignBlock, DevelopBlock, SignBlock, MoreBlock, CopyBlock, TermBlock },
};
</script>
