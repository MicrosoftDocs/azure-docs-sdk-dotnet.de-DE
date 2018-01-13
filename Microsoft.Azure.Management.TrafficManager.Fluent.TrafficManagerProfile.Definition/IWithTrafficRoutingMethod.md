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
            Die Phase der Traffic Manager-Profildefinition ermöglicht die datenverkehrrouting-Methode für das Profil an.
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
            Gibt an, dass Endbenutzer-Datenverkehrs basierend auf dem geografischen Standort des Endpunkts in der Nähe Benutzer weitergeleitet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
            Gibt an, dass Endbenutzer Datenverkehr sollen, an den Endpunkt weitergeleitet werden, d. h. basierend auf seiner Priorität verwenden Sie den Endpunkt mit der höchsten Priorität und ist er nicht verfügbaren Fallback auf den Endpunkt mit höchster Priorität weiter.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
        <param name="routingMethod">Die datenverkehrrouting-Methode für das Profil.</param>
        <summary>
            Geben Sie die datenverkehrrouting-Methode für das Profil ein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
            Gibt an, dass Endbenutzer-Datenverkehrs an die Endpunkte basierend auf der an den Endpunkt zugewiesenen Gewichtung verteilt werden sollen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>