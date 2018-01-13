<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConnectionString(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithConnectionString&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT">Der Typ der Ressource.</typeparam>
    <summary>
            Eine Web-app Definition Phase Verbindungszeichenfolgen festgelegt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name">Name der Verbindungszeichenfolge:</param>
        <param name="value">Der Wert der Verbindungszeichenfolge.</param>
        <param name="type">Der Verbindungstyp Zeichenfolge.</param>
        <summary>
            Die Web-app hinzugefügt eine Verbindungszeichenfolge.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IWithCreate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Definition.IWithCreate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType" />
      </Parameters>
      <Docs>
        <param name="name">Name der Verbindungszeichenfolge:</param>
        <param name="value">Der Wert der Verbindungszeichenfolge.</param>
        <param name="type">Der Verbindungstyp Zeichenfolge.</param>
        <summary>
            Die Web-app hinzugefügt eine Verbindungszeichenfolge. Diese Verbindungszeichenfolge wird ebenfalls nach einem slotaustausch Bereitstellung ausgetauscht werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>