<Type Name="IWithReverseFQDN" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN">
  <TypeSignature Language="C#" Value="public interface IWithReverseFQDN" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithReverseFQDN" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithReverseFQDN" />
  <TypeSignature Language="F#" Value="type IWithReverseFQDN = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine öffentliche IP-adressendefinition ermöglicht die reverse FQDN angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutReverseFqdn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithoutReverseFqdn() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN.WithoutReverseFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutReverseFqdn () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutReverseFqdn : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithReverseFQDN.WithoutReverseFqdn " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellt sicher, dass kein reverse FQDN verwendet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithReverseFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithReverseFqdn (string reverseFQDN);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate WithReverseFqdn(string reverseFQDN) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithReverseFQDN.WithReverseFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithReverseFqdn (reverseFQDN As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithReverseFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate" Usage="iWithReverseFQDN.WithReverseFqdn reverseFQDN" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reverseFQDN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="reverseFQDN">Der reverse FQDN zuweisen.</param>
        <summary>
            Gibt den reverse FQDN in diese öffentliche IP-Adresse zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>