22. Generate Parenthesesclass Solution {
public:
    vector<string> generateParenthesis(int n) {
        vector<string> result;
      
        // Define recursive function to generate valid parentheses combinations
        // Parameters:
        // - openCount: number of opening parentheses used so far
        // - closeCount: number of closing parentheses used so far
        // - currentString: current parentheses string being built
        function<void(int, int, string)> backtrack = [&](int openCount, int closeCount, string currentString) {
            // Base case: invalid conditions
            // 1. Too many open parentheses
            // 2. Too many close parentheses  
            // 3. More close pa
            backtrack(openCount, closeCount + 1, currentString + ")");
        };
      
        // Start the recursive generation with empty string and zero counts
        backtrack(0, 0, "");
      
        return result;
    }
};
