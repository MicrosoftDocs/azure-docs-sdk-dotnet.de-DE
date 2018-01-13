<Type Name="IWithStateOrProvince&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithStateOrProvince&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithStateOrProvince&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStateOrProvince`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithStateOrProvince`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStateOrProvince(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithStateOrProvince&lt;'ParentT&gt; = interface" />
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
            Die Phase der Kontakt Definition ermöglicht Bundesland/Kanton festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithStateOrProvince">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithCountry&lt;ParentT&gt; WithStateOrProvince (string stateOrProvince);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithCountry`1&lt;!ParentT&gt; WithStateOrProvince(string stateOrProvince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithStateOrProvince`1.WithStateOrProvince(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStateOrProvince (stateOrProvince As String) As IWithCountry(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStateOrProvince : string -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithCountry&lt;'ParentT&gt;" Usage="iWithStateOrProvince.WithStateOrProvince stateOrProvince" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithCountry&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateOrProvince" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="stateOrProvince">Das Bundesland oder Kanton der Adresse.</param>
        <summary>
            Gibt an, das Bundesland oder Kanton der Adresse.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>