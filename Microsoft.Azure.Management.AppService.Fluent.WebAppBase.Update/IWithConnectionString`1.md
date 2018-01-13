<Type Name="IWithConnectionString&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithConnectionString&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConnectionString`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1" />
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
            Eine Web-app aktualisieren Stufe ermöglicht Verbindungszeichenfolgen festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
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
        <return>Die nächste Phase des Web-app-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithConnectionStringStickiness">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithConnectionStringStickiness (string name, bool sticky);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithConnectionStringStickiness(string name, bool sticky) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithConnectionStringStickiness(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConnectionStringStickiness (name As String, sticky As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithConnectionStringStickiness : string * bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithConnectionStringStickiness (name, sticky)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sticky" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">Name der Verbindungszeichenfolge:</param>
        <param name="sticky">"True", wenn die Verbindungszeichenfolge in das Einschubfach während einen Austausch sticks.</param>
        <summary>
            Ändert die Klebrigkeit eine Verbindungszeichenfolge an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Web-app-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutConnectionString (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutConnectionString(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithoutConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutConnectionString (name As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutConnectionString : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithoutConnectionString name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Name der Verbindungszeichenfolge:</param>
        <summary>
            Entfernt eine Verbindungszeichenfolge aus der Web-app.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Web-app-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStickyConnectionString">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithStickyConnectionString (string name, string value, Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithStickyConnectionString(string name, string value, valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithConnectionString`1.WithStickyConnectionString(System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStickyConnectionString (name As String, value As String, type As ConnectionStringType) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithStickyConnectionString : string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ConnectionStringType -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithConnectionString.WithStickyConnectionString (name, value, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
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
            Die Web-app hinzugefügt eine Verbindungszeichenfolge. Diese Verbindungszeichenfolge, die bei einem Austausch an den Slot verbleibt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Web-app-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>