<Type Name="IWithPostalCode&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPostalCode&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPostalCode`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPostalCode(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPostalCode&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase der Definition des übergeordneten wieder nach dem Anfügen.</typeparam>
    <summary>
            Die Phase der Kontakt Definition ermöglicht Postleitzahl festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPostalCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;ParentT&gt; WithPostalCode (string postalCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode`1&lt;!ParentT&gt; WithPostalCode(string postalCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPostalCode`1.WithPostalCode(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPostalCode (postalCode As String) As IWithPhoneCountryCode(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPostalCode : string -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;'ParentT&gt;" Usage="iWithPostalCode.WithPostalCode postalCode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithPhoneCountryCode&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="postalCode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="postalCode">Die Postleitzahl der Adresse.</param>
        <summary>
            Gibt die Postleitzahl oder die Postleitzahl der Adresse.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>