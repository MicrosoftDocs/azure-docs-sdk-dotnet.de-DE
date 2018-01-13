<Type Name="IWithNestedProfile&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithNestedProfile&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNestedProfile&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNestedProfile`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithNestedProfile`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNestedProfile(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNestedProfile&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp der UpdateDefinitionStages.WithAttach.attach().</typeparam>
    <summary>
            Die Phase der Traffic Manager geschachtelt Profil Endpunkt Definition ermöglicht das Profil an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegionThenThreshold&lt;ParentT&gt; ToProfile (Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile profile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegionThenThreshold`1&lt;!ParentT&gt; ToProfile(class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile profile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithNestedProfile`1.ToProfile(Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToProfile (profile As ITrafficManagerProfile) As IWithSourceTrafficRegionThenThreshold(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToProfile : Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegionThenThreshold&lt;'ParentT&gt;" Usage="iWithNestedProfile.ToProfile profile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegionThenThreshold&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="profile" Type="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
      </Parameters>
      <Docs>
        <param name="profile">Die geschachtelte Traffic Manager-Profil.</param>
        <summary>
            Gibt eine geschachtelte Traffic Manager-Profil für den Endpunkt an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>