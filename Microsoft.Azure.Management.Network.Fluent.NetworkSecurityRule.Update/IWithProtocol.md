<Type Name="IWithProtocol" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol">
  <TypeSignature Language="C#" Value="public interface IWithProtocol" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithProtocol" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithProtocol" />
  <TypeSignature Language="F#" Value="type IWithProtocol = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der die Beschreibung der Sicherheitsregel ermöglicht das Protokoll, das die Regel gilt angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAnyProtocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithAnyProtocol ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithAnyProtocol() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol.WithAnyProtocol" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAnyProtocol () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAnyProtocol : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithProtocol.WithAnyProtocol " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Macht diese Regel auf ein unterstütztes Protokoll angewendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithProtocol">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithProtocol (string protocol);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate WithProtocol(string protocol) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IWithProtocol.WithProtocol(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProtocol (protocol As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithProtocol : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate" Usage="iWithProtocol.WithProtocol protocol" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol">Einer der unterstützten Protokolle.</param>
        <summary>
            Gibt das Protokoll, dem diese Regel gilt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>