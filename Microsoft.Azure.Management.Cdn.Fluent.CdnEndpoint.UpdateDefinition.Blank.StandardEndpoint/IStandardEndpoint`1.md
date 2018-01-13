<Type Name="IStandardEndpoint&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IStandardEndpoint&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStandardEndpoint`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStandardEndpoint(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IStandardEndpoint&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten CDN-Profil Updates wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der CDN-Profil Endpunktdefinition den Ursprung angeben können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithOrigin (string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithOrigin(string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint`1.WithOrigin(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOrigin (originHostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOrigin : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iStandardEndpoint.WithOrigin originHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originHostName">Hostname des Ursprungs.</param>
        <summary>
            Gibt den Ursprung des CDN-Endpunkts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithOrigin">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt; WithOrigin (string originName, string originHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach`1&lt;!ParentT&gt; WithOrigin(string originName, string originHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint`1.WithOrigin(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOrigin (originName As String, originHostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOrigin : string * string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iStandardEndpoint.WithOrigin (originName, originHostName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originName" Type="System.String" />
        <Parameter Name="originHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originName">Der Name des Ursprungs.</param>
        <param name="originHostName">Hostname des Ursprungs.</param>
        <summary>
            Gibt den Ursprung des CDN-Endpunkts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>