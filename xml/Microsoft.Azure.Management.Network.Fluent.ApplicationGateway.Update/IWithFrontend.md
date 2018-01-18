<Type Name="IWithFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend">
  <TypeSignature Language="C#" Value="public interface IWithFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend" />
  <TypeSignature Language="F#" Value="type IWithFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d43c3-101">Die Phase eines um Front-End-IP-Konfigurationen zu ändern, sodass Anwendung Gateway-Updates.</span><span class="sxs-lookup"><span data-stu-id="d43c3-101">The stage of an application gateway update allowing to modify frontend IP configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefinePrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePrivateFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d43c3-102">Startet die Definition der standardmäßige private Front-End-IP-Konfiguration, erstellen einen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d43c3-102">Begins the definition of the default private frontend IP configuration, creating one if it does not already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-103">Die erste Phase der Front-End-Definition.</span><span class="sxs-lookup"><span data-stu-id="d43c3-103">The first stage of a frontend definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefinePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePublicFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d43c3-104">Startet die Definition der standardmäßige öffentliche Front-End-IP-Konfiguration, erstellen einen, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d43c3-104">Begins the definition of the default public frontend IP configuration, creating one if it does not already exist.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-105">Die erste Phase der Front-End-Definition.</span><span class="sxs-lookup"><span data-stu-id="d43c3-105">The first stage of a frontend definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdateFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdateFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName"><span data-ttu-id="d43c3-106">Der Name einer vorhandenen Front-End-IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d43c3-106">The name of an existing frontend IP configuration.</span></span></param>
        <summary>
            <span data-ttu-id="d43c3-107">Startet das Update einer vorhandenen Front-End-IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d43c3-107">Begins the update of an existing frontend IP configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-108">Die erste Phase der Aktualisierung der Front-End-IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d43c3-108">The first stage of the frontend IP configuration update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdatePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdatePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d43c3-109">Beginnt die Aktualisierung der öffentliche Front-End-IP-Konfiguration an, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="d43c3-109">Begins the update of the public frontend IP configuration, if it exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-110">Die erste Phase eines Front-End-Update oder Null, wenn keine öffentliche Front-End-vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d43c3-110">The first stage of a frontend update or null if no public frontend exists.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName"><span data-ttu-id="d43c3-111">Der Name der Front-End-IP-Konfiguration entfernen.</span><span class="sxs-lookup"><span data-stu-id="d43c3-111">The name of the frontend IP configuration to remove.</span></span></param>
        <summary>
            <span data-ttu-id="d43c3-112">Entfernt die angegebene Front-End-IP-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="d43c3-112">Removes the specified frontend IP configuration.</span></span>
            <span data-ttu-id="d43c3-113">Beachten Sie, dass ein Front-End-verwiesen wird, indem Sie andere Einstellungen entfernen das Anwendungsgateway umgebrochen werden kann.</span><span class="sxs-lookup"><span data-stu-id="d43c3-113">Note that removing a frontend referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-114">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="d43c3-114">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d43c3-115">Gibt an, dass das Anwendungsgateway sollte nicht privat sein, d. h. seine Endponts sollte nicht intern von innerhalb des virtuellen Netzwerks zugänglich.</span><span class="sxs-lookup"><span data-stu-id="d43c3-115">Specifies that the application gateway should not be private, i.e. its endponts should not be internally accessible from within the virtual network.</span></span>
            <span data-ttu-id="d43c3-116">Beachten Sie, wenn alle anderen Einstellungen verweisen auf das private Front-End vorhanden sind, entfernen sie das Anwendungsgateway unterbrechen kann.</span><span class="sxs-lookup"><span data-stu-id="d43c3-116">Note that if there are any other settings referencing the private frontend, removing it may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-117">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="d43c3-117">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d43c3-118">Gibt an, dass das Anwendungsgateway Internetzugriff nicht sein sollte.</span><span class="sxs-lookup"><span data-stu-id="d43c3-118">Specifies that the application gateway should not be Internet-facing.</span></span>
            <span data-ttu-id="d43c3-119">Beachten Sie, wenn alle anderen Einstellungen verweisen auf das öffentliche Front-End vorhanden sind, entfernen sie das Anwendungsgateway unterbrechen kann.</span><span class="sxs-lookup"><span data-stu-id="d43c3-119">Note that if there are any other settings referencing the public frontend, removing it may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d43c3-120">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="d43c3-120">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>