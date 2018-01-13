<Type Name="IWithSourceAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourceAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceAddress&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceAddress`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourceAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceAddress(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSourceAddress&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der Regel der Definition des Netzwerks ermöglicht die Quelladresse angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;ParentT&gt; FromAddress (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort`1&lt;!ParentT&gt; FromAddress(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourceAddress`1.FromAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAddress (cidr As String) As IWithSourcePort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;'ParentT&gt;" Usage="iWithSourceAddress.FromAddress cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">Eine IP-Adresspräfix in der CIDR-Schreibweise ausgedrückt.</param>
        <summary>
            Gibt das Adresspräfix der Datenverkehr-Quelle für das diese Regel gilt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="FromAnyAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;ParentT&gt; FromAnyAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort`1&lt;!ParentT&gt; FromAnyAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourceAddress`1.FromAnyAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function FromAnyAddress () As IWithSourcePort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromAnyAddress : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;'ParentT&gt;" Usage="iWithSourceAddress.FromAnyAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithSourcePort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass die Regel für alle Quelladresse Datenverkehr gelten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>