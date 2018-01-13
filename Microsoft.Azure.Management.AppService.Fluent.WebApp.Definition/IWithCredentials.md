<Type Name="IWithCredentials" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials">
  <TypeSignature Language="C#" Value="public interface IWithCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCredentials" />
  <TypeSignature Language="F#" Value="type IWithCredentials = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition einer Web-app ermöglicht Docker Registrierung Anmeldeinformationen festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithCredentials (string username, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithCredentials(string username, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials.WithCredentials(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCredentials (username As String, password As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithCredentials : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand" Usage="iWithCredentials.WithCredentials (username, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="username">Der Benutzername für Docker Hub oder Docker-Registrierung.</param>
        <param name="password">Das Kennwort für Docker Hub oder Docker-Registrierung.</param>
        <summary>
            Gibt den Benutzernamen und das Kennwort für Docker Hub oder Docker-Registrierung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>