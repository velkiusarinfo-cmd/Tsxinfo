import { Menu, MessageSquare } from "lucide-react"
import { Button } from "@/components/ui/button"

// Agent data for the first table
const agentData1 = [
  { id: 735, phone: "+916003376594" },
  { id: 1309, phone: "+601043881128" },
  { id: 1305, phone: "+919678210580" },
  { id: 1301, phone: "+916003406572" },
  { id: 736, phone: "+919101011483" },
  { id: 1307, phone: "+17794568474" },
  { id: 1308, phone: "+17152148865" },
  { id: 734, phone: "+918011691780" },
  { id: 1306, phone: "+601426722207" },
]

// Agent data for the second table
const agentData2 = [
  { id: 679, phone: "+601139946073" },
  { id: 432, phone: "+601139946039" },
  { id: 71, phone: "+601139946084" },
  { id: 541, phone: "+601139945947" },
  { id: 578, phone: "+601139946105" },
  { id: 894, phone: "+601760649669" },
  { id: 540, phone: "+601760711103" },
]

export default function CustomerServicePage() {
  return (
    <div className="min-h-screen bg-gray-50">
      {/* Header */}
      <header className="bg-white border-b-4 border-red-600 px-4 py-3">
        <div className="flex items-center justify-between">
          <div className="flex items-center gap-3">
            <Button variant="ghost" size="sm" className="p-1">
              <Menu className="h-6 w-6" />
            </Button>
            <div className="flex items-center">
              <span className="text-red-600 font-bold text-lg">ecom</span>
              <span className="bg-black text-white px-2 py-1 text-sm font-bold ml-1">velki</span>
            </div>
          </div>
          <div className="text-red-600 font-semibold text-lg">à¦•à¦¾à¦¸à§à¦Ÿà¦®à¦¾à¦° à¦¸à¦¾à¦°à§à¦­à¦¿à¦¸</div>
        </div>
      </header>

      <div className="p-4 space-y-6">
        {/* First Table Section */}
        <div>
          <h2 className="text-lg font-semibold mb-4 text-gray-800">
            à¦¸à¦¾à¦¬ à¦à¦¡à¦®à¦¿à¦¨ à§® à¦à¦° à¦…à¦§à§€à¦¨à§‡ à¦¸à§à¦ªà¦¾à¦° à¦à¦œà§‡à¦¨à§à¦Ÿ à§©à§« à¦à¦° à¦…à¦§à§€à¦¨à§‡ à¦¸à¦°à§à¦¬à¦®à§‹à¦Ÿ à¦®à¦¾à¦¸à§à¦Ÿà¦¾à¦° à¦à¦œà§‡à¦¨à§à¦Ÿ à¦†à¦›à§‡ à§¯ à¦œà¦¨
          </h2>

          <div className="bg-white rounded-lg shadow-sm overflow-hidden">
            <table className="w-full">
              <thead className="bg-gray-100">
                <tr>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">ID NO</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">AGENT</th>
                  <th className="px-4 py-3 text-center font-semibold text-gray-700 border-r">APP</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">PHONE NUMBER</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700">COMPLAIN</th>
                </tr>
              </thead>
              <tbody>
                {agentData1.map((agent, index) => (
                  <tr key={agent.id} className={index % 2 === 0 ? "bg-white" : "bg-gray-50"}>
                    <td className="px-4 py-3 border-r border-gray-200 font-medium">{agent.id}</td>
                    <td className="px-4 py-3 border-r border-gray-200">à¦®à¦¾à¦¸à§à¦Ÿà¦¾à¦°</td>
                    <td className="px-4 py-3 border-r border-gray-200 text-center">
                      <div className="inline-flex items-center justify-center w-8 h-8 bg-green-500 rounded-lg">
                        <MessageSquare className="h-5 w-5 text-white" />
                      </div>
                    </td>
                    <td className="px-4 py-3 border-r border-gray-200 text-red-600 font-medium">{agent.phone}</td>
                    <td className="px-4 py-3 text-red-600 font-medium">à¦…à¦­à¦¿à¦¯à§‹à¦—</td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        </div>

        {/* Second Table Section */}
        <div>
          <h2 className="text-lg font-semibold mb-4 text-gray-800">
            à¦¸à¦¾à¦¬ à¦à¦¡à¦®à¦¿à¦¨ à§ª à¦à¦° à¦…à¦§à§€à¦¨à§‡ à¦¸à§à¦ªà¦¾à¦° à¦à¦œà§‡à¦¨à§à¦Ÿ à§­à§¬ à¦à¦° à¦…à¦§à§€à¦¨à§‡ à¦¸à¦°à§à¦¬à¦®à§‹à¦Ÿ à¦®à¦¾à¦¸à§à¦Ÿà¦¾à¦° à¦à¦œà§‡à¦¨à§à¦Ÿ à¦†à¦›à§‡ à§¯ à¦œà¦¨
          </h2>

          <div className="bg-white rounded-lg shadow-sm overflow-hidden">
            <table className="w-full">
              <thead className="bg-gray-100">
                <tr>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">ID NO</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">AGENT</th>
                  <th className="px-4 py-3 text-center font-semibold text-gray-700 border-r">APP</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700 border-r">PHONE NUMBER</th>
                  <th className="px-4 py-3 text-left font-semibold text-gray-700">COMPLAIN</th>
                </tr>
              </thead>
              <tbody>
                {agentData2.map((agent, index) => (
                  <tr key={agent.id} className={index % 2 === 0 ? "bg-white" : "bg-gray-50"}>
                    <td className="px-4 py-3 border-r border-gray-200 font-medium">{agent.id}</td>
                    <td className="px-4 py-3 border-r border-gray-200">à¦®à¦¾à¦¸à§à¦Ÿà¦¾à¦°</td>
                    <td className="px-4 py-3 border-r border-gray-200 text-center">
                      <div className="inline-flex items-center justify-center w-8 h-8 bg-green-500 rounded-lg">
                        <MessageSquare className="h-5 w-5 text-white" />
                      </div>
                    </td>
                    <td className="px-4 py-3 border-r border-gray-200 text-red-600 font-medium">{agent.phone}</td>
                    <td className="px-4 py-3 text-red-600 font-medium">à¦…à¦­à¦¿à¦¯à§‹à¦—</td>
                  </tr>
                ))}
              </tbody>
            </table>
          </div>
        </div>
      </div>

      {/* Footer URL */}
      <div className="text-center py-4 text-gray-500 text-sm">winpbubd.com</div>
    </div>
  )
}
