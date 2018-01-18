<Type Name="IWithTrafficRoutingMethod" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod">
  <TypeSignature Language="C#" Value="public interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTrafficRoutingMethod" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTrafficRoutingMethod" />
  <TypeSignature Language="F#" Value="type IWithTrafficRoutingMethod = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="43252-101">Die Phase der Traffic Manager-Profildefinition ermöglicht die datenverkehrrouting-Methode für das Profil an.</span><span class="sxs-lookup"><span data-stu-id="43252-101">The stage of the traffic manager profile definition allowing to specify the traffic routing method for the profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGeographicBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithGeographicBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithGeographicBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithGeographicBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeographicBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithGeographicBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithGeographicBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithPerformanceBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPerformanceBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPerformanceBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithPerformanceBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPerformanceBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithPerformanceBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithPerformanceBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43252-102">Gibt an, dass Endbenutzer-Datenverkehrs basierend auf dem geografischen Standort des Endpunkts in der Nähe Benutzer weitergeleitet werden soll.</span><span class="sxs-lookup"><span data-stu-id="43252-102">Specifies that end user traffic should be routed based on the geographic location of the endpoint close to user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="43252-103">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="43252-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPriorityBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPriorityBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithPriorityBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithPriorityBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriorityBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithPriorityBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithPriorityBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43252-104">Gibt an, dass Endbenutzer Datenverkehr sollen, an den Endpunkt weitergeleitet werden, d. h. basierend auf seiner Priorität verwenden Sie den Endpunkt mit der höchsten Priorität und ist er nicht verfügbaren Fallback auf den Endpunkt mit höchster Priorität weiter.</span><span class="sxs-lookup"><span data-stu-id="43252-104">Specifies that end user traffic should be routed to the endpoint based on its priority i.e. use the endpoint with highest priority and if it is not available fallback to next highest priority endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="43252-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="43252-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithTrafficRoutingMethod (Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithTrafficRoutingMethod(class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod routingMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithTrafficRoutingMethod(Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTrafficRoutingMethod (routingMethod As TrafficRoutingMethod) As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithTrafficRoutingMethod : Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithTrafficRoutingMethod routingMethod" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routingMethod" Type="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod" />
      </Parameters>
      <Docs>
        <param name="routingMethod"><span data-ttu-id="43252-106">Die datenverkehrrouting-Methode für das Profil.</span><span class="sxs-lookup"><span data-stu-id="43252-106">The traffic routing method for the profile.</span></span></param>
        <summary>
            <span data-ttu-id="43252-107">Geben Sie die datenverkehrrouting-Methode für das Profil ein.</span><span class="sxs-lookup"><span data-stu-id="43252-107">Specify the traffic routing method for the profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="43252-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="43252-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWeightBasedRouting">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithWeightBasedRouting ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint WithWeightBasedRouting() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithTrafficRoutingMethod.WithWeightBasedRouting" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWeightBasedRouting () As IWithEndpoint" />
      <MemberSignature Language="F#" Value="abstract member WithWeightBasedRouting : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint" Usage="iWithTrafficRoutingMethod.WithWeightBasedRouting " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Definition.IWithEndpoint</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="43252-109">Gibt an, dass Endbenutzer-Datenverkehrs an die Endpunkte basierend auf der an den Endpunkt zugewiesenen Gewichtung verteilt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="43252-109">Specifies that end user traffic should be distributed to the endpoints based on the weight assigned to the endpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="43252-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="43252-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>