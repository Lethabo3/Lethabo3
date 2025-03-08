#include <stdio.h>
#include <string.h>

// Lethabo: CS Student Config
char name[] = "Lethabo";
char anime[] = "Naruto";
char current_watch[] = "Orb: On the Movement of the Earth";
char coding_mode[] = "AI Vibe Coding";
char stack[] = "Python, C++, JS";

// ASCII Art: Lethabo
void print_name() {
    printf("  _      ______ _______ _    _   ___   ______ \n");
    printf(" | |    |  ____|__   __| |  | | / _ \\ /  __  \\\n");
    printf(" | |    | |__     | |  | |__| || |_| |  /  \\  |\n");
    printf(" | |    |  __|    | |  |  __  ||  _  | /   /  |\n");
    printf(" | |____| |____   | |  | |  | || | | |\\  /   |\n");
    printf(" |______|______|  |_|  |_|  |_|_| |_|_|\\____/\n");
}

// System Status
void status() {
    printf("Running: %s\n", coding_mode);
    printf("Stack: %s\n", stack);
    printf("Anime: %s\n", anime);
    printf("Watching: %s\n", current_watch);
}

// Main Execution
int main() {
    print_name();
    status();
    printf("Links: [X] [Portfolio] lethabo@code\n");
    return 0;
}
