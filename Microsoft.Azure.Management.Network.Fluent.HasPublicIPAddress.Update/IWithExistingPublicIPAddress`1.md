<Type Name="IWithExistingPublicIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithExistingPublicIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithExistingPublicIPAddress&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingPublicIPAddress`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithExistingPublicIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingPublicIPAddress(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithExistingPublicIPAddress&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT">die nächste Phase des Updates.</typeparam>
    <summary>
            Die Phase des Updates ermöglicht, eine vorhandene öffentliche IP-Adresse die Ressource zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithExistingPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithExistingPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithExistingPublicIPAddress`1.WithExistingPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPublicIPAddress (publicIPAddress As IPublicIPAddress) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; 'ReturnT" Usage="iWithExistingPublicIPAddress.WithExistingPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">Eine vorhandene öffentliche IP-Adresse.</param>
        <summary>
            Ordnet eine vorhandene öffentliche IP-Adresse der Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithExistingPublicIPAddress (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithExistingPublicIPAddress(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithExistingPublicIPAddress`1.WithExistingPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPublicIPAddress (resourceId As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPublicIPAddress : string -&gt; 'ReturnT" Usage="iWithExistingPublicIPAddress.WithExistingPublicIPAddress resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">Die Ressourcen-ID, eine vorhandene öffentliche IP-Adresse.</param>
        <summary>
            Ordnet eine vorhandene öffentliche IP-Adresse der Ressource.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithoutPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithoutPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithExistingPublicIPAddress`1.WithoutPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPublicIPAddress () As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithoutPublicIPAddress : unit -&gt; 'ReturnT" Usage="iWithExistingPublicIPAddress.WithoutPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Entfernt den Verweis auf eine öffentliche IP-Adresse an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>