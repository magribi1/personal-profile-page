// Edit this list to update the Skills section.
const skills = [
  {
    group: 'Networking',
    items: ['TCP/IP', 'OSI Model', 'IPv4/IPv6', 'Subnetting', 'VLANs & Trunking', 'Inter-VLAN Routing', 'Static Routing', 'OSPF', 'Troubleshooting', 'Cisco Packet Tracer'],
  },
  {
    group: 'Network security',
    items: ['Firewall configuration', 'Firewall policies & ACLs', 'IDS/IPS', 'Security monitoring', 'DoS/DDoS', 'VPN', 'Threat analysis'],
  },
  {
    group: 'Cybersecurity',
    items: ['Ethical hacking', 'Web security', 'OWASP Top 10', 'Vulnerability assessment', 'Reconnaissance', 'Security testing', 'Secure SDLC', 'Threat modeling', 'Risk assessment'],
  },
  {
    group: 'Tools',
    items: ['Nmap', 'Wireshark', 'Burp Suite', 'Metasploit', 'Kali Linux', 'Nessus', 'Huawei USG / eNSP'],
  },
  {
    group: 'Systems & code',
    items: ['Linux', 'Windows', 'Python', 'SQL', 'Git & GitHub', 'HTML, CSS, JS'],
  },
];

const list = document.querySelector('#skills-list');

if (list) {
  list.innerHTML = skills
    .map(
      ({ group, items }) => `
      <div class="skills__group">
        <h3 class="skills__name">${group}</h3>
        <ul class="skills__tags">${items.map((item) => `<li>${item}</li>`).join('')}</ul>
      </div>`
    )
    .join('');
}

document.querySelector('#year').textContent = new Date().getFullYear();
