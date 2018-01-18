<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a601a-101">Die Phase des virtuellen Netzwerks aktualisieren zum Hinzufügen oder entfernen Sie die Subnetze ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="a601a-101">The stage of the virtual network update allowing to add or remove subnets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt; DefineSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.DefineSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSubnet (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;" Usage="iWithSubnet.DefineSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a601a-102">Der Name des neuen Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="a601a-102">The name of the new subnet.</span></span></param>
        <summary>
            <span data-ttu-id="a601a-103">Beginn der Definition eines neuen Teilnetzes mit diesem virtuellen Netzwerk hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="a601a-103">Begins the definition of a new subnet to be added to this virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a601a-104">Die erste Phase des der neuen subnetzdefinition.</span><span class="sxs-lookup"><span data-stu-id="a601a-104">The first stage of the new subnet definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate UpdateSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.UpdateSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithSubnet.UpdateSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a601a-105">Der Name von einem vorhandenen Subnetz.</span><span class="sxs-lookup"><span data-stu-id="a601a-105">The name of an existing subnet.</span></span></param>
        <summary>
            <span data-ttu-id="a601a-106">Startet die Beschreibung eines Updates von einem vorhandenen Subnetz des Netzwerks an.</span><span class="sxs-lookup"><span data-stu-id="a601a-106">Begins the description of an update of an existing subnet of this network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a601a-107">Die erste Stufe der die Beschreibung des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="a601a-107">The first stage of the subnet update description.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithoutSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithoutSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSubnet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithoutSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a601a-108">Der Name des Subnetzes, zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="a601a-108">Name of the subnet to remove.</span></span></param>
        <summary>
            <span data-ttu-id="a601a-109">Entfernt ein Subnetz aus dem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="a601a-109">Removes a subnet from the virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a601a-110">Die nächste Phase des virtuellen Netzwerks Updates.</span><span class="sxs-lookup"><span data-stu-id="a601a-110">The next stage of the virtual network update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet (string name, string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnet(string name, string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String, cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnet (name, cidr)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a601a-111">Der Name, mit dem Subnetz zuweisen.</span><span class="sxs-lookup"><span data-stu-id="a601a-111">The name to assign to the subnet.</span></span></param>
        <param name="cidr"><span data-ttu-id="a601a-112">Der Adressraum des Subnetzes innerhalb des Adressraums des Netzwerks mithilfe der CIDR-Notation.</span><span class="sxs-lookup"><span data-stu-id="a601a-112">The address space of the subnet, within the address space of the network, using the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="a601a-113">Das virtuelle Netzwerk hinzugefügt explizit ein Subnetz.</span><span class="sxs-lookup"><span data-stu-id="a601a-113">Explicitly adds a subnet to the virtual network.</span></span>
            <span data-ttu-id="a601a-114">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neues Subnetz wird zum Netzwerk hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a601a-114">Note this method's effect is additive, i.e. each time it is used, a new subnet is added to the network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a601a-115">Die nächste Phase des virtuellen Netzwerks Updates.</span><span class="sxs-lookup"><span data-stu-id="a601a-115">The next stage of the virtual network update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets (System.Collections.Generic.IDictionary&lt;string,string&gt; nameCidrPairs);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithSubnets(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; nameCidrPairs) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithSubnet.WithSubnets(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnets (nameCidrPairs As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnets : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithSubnet.WithSubnets nameCidrPairs" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameCidrPairs" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="nameCidrPairs"><span data-ttu-id="a601a-116">Eine Zuordnung der CIDR-Adressen für die Subnetze, die indiziert werden, durch den Namen aller Subnetze hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="a601a-116">A  Map of CIDR addresses for the subnets, indexed by the name of each subnet to be added.</span></span></param>
        <summary>
            <span data-ttu-id="a601a-117">Explizit definiert alle Subnetze im virtuellen Netzwerk basierend auf der bereitgestellten Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="a601a-117">Explicitly defines all the subnets in the virtual network based on the provided map.</span></span>
            <span data-ttu-id="a601a-118">Dies ersetzt keine zuvor vorhandenen Subnetze.</span><span class="sxs-lookup"><span data-stu-id="a601a-118">This replaces any previously existing subnets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a601a-119">Die nächste Phase des virtuellen Netzwerks Updates.</span><span class="sxs-lookup"><span data-stu-id="a601a-119">The next stage of the virtual network update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>