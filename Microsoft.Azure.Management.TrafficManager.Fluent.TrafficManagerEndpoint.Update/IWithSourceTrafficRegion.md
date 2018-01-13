<Type Name="IWithSourceTrafficRegion" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion">
  <TypeSignature Language="C#" Value="public interface IWithSourceTrafficRegion" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceTrafficRegion" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceTrafficRegion" />
  <TypeSignature Language="F#" Value="type IWithSourceTrafficRegion = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Traffic Manager Endpunkt Update ermöglichen den Speicherort der externen oder geschachtelte Profil Endpunkte angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromRegion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate FromRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region location);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate FromRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IWithSourceTrafficRegion.FromRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromRegion (location As Region) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate" Usage="iWithSourceTrafficRegion.FromRegion location" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="location">Der Speicherort.</param>
        <summary>
            Gibt die Region des Endpunkts, der verwendet wird, wenn die Leistungsbasierte Routingmethode TrafficRoutingMethod.PERFORMANCE für das Profil aktiviert ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Updates für den Endpunkt.</return>
      </Docs>
    </Member>
  </Members>
</Type>