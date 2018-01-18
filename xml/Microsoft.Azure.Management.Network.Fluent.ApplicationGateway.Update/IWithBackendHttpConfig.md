<Type Name="IWithBackendHttpConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfig" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7fd68-101">Die Phase eines Anwendung Gateway Updates, sodass Back-End-HTTP-Konfigurationen ändern.</span><span class="sxs-lookup"><span data-stu-id="7fd68-101">The stage of an application gateway update allowing to modify backend HTTP configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.DefineBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackendHttpConfiguration (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithBackendHttpConfig.DefineBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7fd68-102">Ein eindeutiger Name für die Back-End-HTTP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="7fd68-102">A unique name for the backend HTTP configuration.</span></span></param>
        <summary>
            <span data-ttu-id="7fd68-103">Beginn der Definition einer neuen Anwendung Gateway Back-End-HTTP-Konfiguration an das Gateway angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="7fd68-103">Begins the definition of a new application gateway backend HTTP configuration to be attached to the gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7fd68-104">Die erste Phase der Definition des Back-End-HTTP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="7fd68-104">The first stage of the backend HTTP configuration definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate UpdateBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate UpdateBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.UpdateBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate" Usage="iWithBackendHttpConfig.UpdateBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7fd68-105">Der Name einer vorhandenen Back-End-HTTP-Konfiguration auf diese Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="7fd68-105">The name of an existing backend HTTP configuration on this application gateway.</span></span></param>
        <summary>
            <span data-ttu-id="7fd68-106">Startet das Update einer Back-End-HTTP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="7fd68-106">Begins the update of a backend HTTP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7fd68-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="7fd68-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.WithoutBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithBackendHttpConfig.WithoutBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7fd68-108">Der Name einer vorhandenen Back-End-HTTP-Konfiguration auf diese Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="7fd68-108">The name of an existing backend HTTP configuration on this application gateway.</span></span></param>
        <summary>
            <span data-ttu-id="7fd68-109">Entfernt die angegebene Back-End-HTTP-Konfiguration zwischen diesem Anwendungsgateway an.</span><span class="sxs-lookup"><span data-stu-id="7fd68-109">Removes the specified backend HTTP configuration from this application gateway.</span></span>
            <span data-ttu-id="7fd68-110">Beachten Sie, dass eine Back-End-HTTP-Konfiguration verwiesen wird, indem Sie andere Einstellungen entfernt das Anwendungsgateway umgebrochen werden kann.</span><span class="sxs-lookup"><span data-stu-id="7fd68-110">Note that removing a backend HTTP configuration referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7fd68-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="7fd68-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>