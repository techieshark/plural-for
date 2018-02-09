//@flow

/**
 * Pluralize a `singular`-form word by adding 's' to the end, or (if provided) returning the `plural` form.
 * @param {number} n determines if the word is pluralized (true for all but n=1).
 * @param {string} singular - the singular word to pluralize.
 * @param {string} plural - the plural form of the word (when not simply singular + "s").
 */
function pluralFor(n: number, singular: string, plural?: string): string {
  if (!plural) plural = singular + 's'; // plural not needed for simple cases when adding 's' works.
  return n === 1 ? singular : plural;
}

module.exports = pluralFor;