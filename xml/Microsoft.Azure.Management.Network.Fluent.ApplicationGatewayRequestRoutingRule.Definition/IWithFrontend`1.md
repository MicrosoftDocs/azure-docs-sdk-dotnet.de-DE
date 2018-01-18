<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="02297-101">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="02297-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="02297-102">Die Phase der ein vorhandenes Anwendungsgateway request routing an das Front-End für die Regel angewendet, sodass Regeldefinition.</span><span class="sxs-lookup"><span data-stu-id="02297-102">The stage of an application gateway request routing rule definition allowing to specify the frontend for the rule to apply to.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;ParentT&gt; FromPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort`1&lt;!ParentT&gt; FromPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontend`1.FromPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02297-103">Aktiviert die Regel an, das Anwendungsgateway private (intern) Front-End.</span><span class="sxs-lookup"><span data-stu-id="02297-103">Enables the rule to apply to the application gateway's private (internal) frontend.</span></span>
            <span data-ttu-id="02297-104">Wenn die private Front-End-IP-Konfiguration noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt.</span><span class="sxs-lookup"><span data-stu-id="02297-104">If the private frontend IP configuration does not yet exist, it will be created under an auto-generated name.</span></span>
            <span data-ttu-id="02297-105">Das Anwendungsgateway kein Subnetz für die private Front-End angegeben, wird eine, wenn ein bestimmtes Subnetz angegeben wird, in der Anwendung Gatewaydefinition optionalen Einstellungen, die mit withExistingSubnet(...) automatisch erstellt.</span><span class="sxs-lookup"><span data-stu-id="02297-105">If the application gateway does not have a subnet specified for its private frontend, one will be created automatically, unless a specific subnet is specified in the application gateway definition's optional settings using withExistingSubnet(...).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="02297-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="02297-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;ParentT&gt; FromPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort`1&lt;!ParentT&gt; FromPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontend`1.FromPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02297-107">Aktiviert die Regel, die für das Anwendungsgateway öffentlichen (Internetverbindung) Front-End-gelten.</span><span class="sxs-lookup"><span data-stu-id="02297-107">Enables the rule to apply to the application gateway's public (Internet-facing) frontend.</span></span>
            <span data-ttu-id="02297-108">Wenn die öffentliche Front-End-IP-Konfiguration noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt.</span><span class="sxs-lookup"><span data-stu-id="02297-108">If the public frontend IP configuration does not yet exist, it will be created under an auto-generated name.</span></span>
            <span data-ttu-id="02297-109">Verfügt das Anwendungsgateway keine öffentliche IP-Adresse für die öffentliche Front-End angegeben, wird eine automatisch erstellt, es sei denn, eine bestimmte öffentliche IP-Adresse angegeben wird, in der Anwendung Gatewaydefinition optionalen Einstellungen, die mit withExistingPublicIPAddress(...) oder withNewPublicIPAddress(...).</span><span class="sxs-lookup"><span data-stu-id="02297-109">If the application gateway does not have a public IP address specified for its public frontend, one will be created automatically, unless a specific public IP address is specified in the application gateway definition's optional settings using withExistingPublicIPAddress(...) or  withNewPublicIPAddress(...).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="02297-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="02297-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>