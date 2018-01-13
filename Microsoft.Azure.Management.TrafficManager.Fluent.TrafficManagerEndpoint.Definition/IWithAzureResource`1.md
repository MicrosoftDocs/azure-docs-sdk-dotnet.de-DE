<Type Name="IWithAzureResource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAzureResource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAzureResource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAzureResource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAzureResource`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAzureResource(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAzureResource&lt;'ParentT&gt; = interface" />
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
            Die Phase des Traffic Manager-Profils Azure Endpunktdefinition, die an die ID des Ziels Azure-Ressource ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToResourceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; ToResourceId (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; ToResourceId(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAzureResource`1.ToResourceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToResourceId (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToResourceId : string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAzureResource.ToResourceId resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">Die Id des Azure-Ressource.</param>
        <summary>
            Gibt die Ressourcen-ID des Azure-Ressource an.
            Unterstützte Azure-Ressourcen sind Cloud-Dienst, WebApp oder die öffentliche IP-Adresse.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>