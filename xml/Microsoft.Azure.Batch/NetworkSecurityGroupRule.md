<Type Name="NetworkSecurityGroupRule" FullName="Microsoft.Azure.Batch.NetworkSecurityGroupRule">
  <TypeSignature Language="C#" Value="public class NetworkSecurityGroupRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkSecurityGroupRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkSecurityGroupRule" />
  <TypeSignature Language="F#" Value="type NetworkSecurityGroupRule = class&#xA;    interface ITransportObjectProvider&lt;NetworkSecurityGroupRule&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8edf4-101">Eine Netzwerksicherheits-Gruppenregel an einen Endpunkt eingehenden anwenden.</span><span class="sxs-lookup"><span data-stu-id="8edf4-101">A network security group rule to apply to an inbound endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkSecurityGroupRule (int priority, Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 priority, valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess access, string sourceAddressPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.NetworkSecurityGroupRule.#ctor(System.Int32,Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (priority As Integer, access As NetworkSecurityGroupRuleAccess, sourceAddressPrefix As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.NetworkSecurityGroupRule : int * Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess * string -&gt; Microsoft.Azure.Batch.NetworkSecurityGroupRule" Usage="new Microsoft.Azure.Batch.NetworkSecurityGroupRule (priority, access, sourceAddressPrefix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="access" Type="Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="8edf4-102">Die Priorität für diese Regel.</span><span class="sxs-lookup"><span data-stu-id="8edf4-102">The priority for this rule.</span></span></param>
        <param name="access"><span data-ttu-id="8edf4-103">Die Aktion, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8edf4-103">The action that should be taken for a specified IP address, subnet range or tag.</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="8edf4-104">Der Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="8edf4-104">The source address prefix or tag to match for the rule.</span></span></param>
        <summary>
            <span data-ttu-id="8edf4-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8edf4-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.NetworkSecurityGroupRule" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Access As NetworkSecurityGroupRuleAccess" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.NetworkSecurityGroupRuleAccess</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8edf4-106">Ruft die Aktion ab, die für eine angegebene IP-Adressen, Subnetzbereich oder Tag ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="8edf4-106">Gets the action that should be taken for a specified IP address, subnet range or tag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8edf4-107">Ruft die Priorität für diese Regel an.</span><span class="sxs-lookup"><span data-stu-id="8edf4-107">Gets the priority for this rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8edf4-108">Prioritäten in einem Pool müssen eindeutig sein und werden in der Reihenfolge ihrer Priorität ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="8edf4-108">Priorities within a pool must be unique and are evaluated in order of priority.</span></span> <span data-ttu-id="8edf4-109">Je niedriger die Nummer ist, desto höher ist die Priorität.</span><span class="sxs-lookup"><span data-stu-id="8edf4-109">The lower the number the higher the priority.</span></span> <span data-ttu-id="8edf4-110">Beispielsweise können Regeln mit den Ordnungszahlen von 150, 250 und 350 angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8edf4-110">For example, rules could be specified with order numbers of 150, 250, and 350.</span></span> <span data-ttu-id="8edf4-111">Die Regel mit der fortlaufenden Nummer der 150 Vorrang vor der Regel mit einer Bestellung von 250.</span><span class="sxs-lookup"><span data-stu-id="8edf4-111">The rule with the order number of 150 takes precedence over the rule that has an order of 250.</span></span> <span data-ttu-id="8edf4-112">Zulässige Prioritäten sind 150-3500 an.</span><span class="sxs-lookup"><span data-stu-id="8edf4-112">Allowed priorities are 150 to 3500.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string" Usage="Microsoft.Azure.Batch.NetworkSecurityGroupRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8edf4-113">Ruft den Quell-Adressenpräfix oder Tag, das für die Regel abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="8edf4-113">Gets the source address prefix or tag to match for the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8edf4-114">Gültige Werte sind eine einzelne IP-Adresse (d. h. 10.10.10.10), die IP-Subnetz (d. h. 192.168.1.0/24), die Standard-Tag oder \* (für alle Adressen).</span><span class="sxs-lookup"><span data-stu-id="8edf4-114">Valid values are a single IP address (i.e. 10.10.10.10), IP subnet (i.e. 192.168.1.0/24), default tag, or \* (for all addresses).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>