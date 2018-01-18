<Type Name="IWithBackendHttpConfiguration&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfiguration(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfiguration&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="c44d4-101">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="c44d4-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="c44d4-102">Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition ermöglicht, die an die Back-End-HTTP-Einstellungen-Konfiguration, um die Weiterleitungsregel mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="c44d4-102">The stage of an application gateway request routing rule definition allowing to specify the backend HTTP settings configuration to associate the routing rule with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c44d4-103">Der Name einer Back-End-HTTP-Einstellungen-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="c44d4-103">The name of a backend HTTP settings configuration.</span></span></param>
        <summary>
            <span data-ttu-id="c44d4-104">Ordnet die angegebene Back-End-HTTP-Einstellungen für Konfiguration dieser Anforderung Routingregel.</span><span class="sxs-lookup"><span data-stu-id="c44d4-104">Associates the specified backend HTTP settings configuration with this request routing rule.</span></span>
            <span data-ttu-id="c44d4-105">Wenn die Back-End-Konfiguration noch nicht vorhanden ist, muss er in den optionalen Teil der Gateway Anwendungsdefinition mit defineBackendHttpConfiguration(...) definiert werden. Die Weiterleitungsregel Anfrage verweist er nur anhand des Namens auf.</span><span class="sxs-lookup"><span data-stu-id="c44d4-105">If the backend configuration does not exist yet, it must be defined in the optional part of the application gateway definition, using  defineBackendHttpConfiguration(...). The request routing rule references it only by name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c44d4-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c44d4-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfiguration`1.ToBackendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpPort (portNumber As Integer) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="c44d4-107">Die Nummer des Ports für eine neue Konfiguration der Back-End-HTTP-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="c44d4-107">The port number for a new backend HTTP settings configuration.</span></span></param>
        <summary>
            <span data-ttu-id="c44d4-108">Erstellt eine Back-End-HTTP-Einstellungen-Konfiguration für die angegebene Back-End-Port und das HTTP-Protokoll, und ordnet diese Anforderung Routingregel.</span><span class="sxs-lookup"><span data-stu-id="c44d4-108">Creates a backend HTTP settings configuration for the specified backend port and the HTTP protocol, and associates it with this request routing rule.</span></span>
            <span data-ttu-id="c44d4-109">Ein automatisch generierter Name wird für den neu erstellten Konfiguration verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c44d4-109">An auto-generated name will be used for this newly created configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c44d4-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c44d4-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>