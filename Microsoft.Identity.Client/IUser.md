<Type Name="IUser" FullName="Microsoft.Identity.Client.IUser">
  <TypeSignature Language="C#" Value="public interface IUser" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUser" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IUser" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUser" />
  <TypeSignature Language="F#" Value="type IUser = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Informationen eines einzelnen Benutzers. Diese Informationen werden verwendet, für die Suche Tokencache und erzwingen die benutzersitzung auf STS Endpont autorisieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisplayableId">
      <MemberSignature Language="C#" Value="public string DisplayableId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.DisplayableId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DisplayableId As String" />
      <MemberSignature Language="F#" Value="member this.DisplayableId : string" Usage="Microsoft.Identity.Client.IUser.DisplayableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen darstellbaren Wert im Format "userPrincipalName" (UPN). Der Wert kann leer sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public string Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As String" />
      <MemberSignature Language="F#" Value="member this.Identifier : string" Usage="Microsoft.Identity.Client.IUser.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Bezeichner für den Benutzer, der von der Bibliothek und der Dienst als ein sicheres Handle für die Benutzeridentität verwendet wird. Darf nicht NULL sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdentityProvider">
      <MemberSignature Language="C#" Value="public string IdentityProvider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IdentityProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.IdentityProvider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdentityProvider As String" />
      <MemberSignature Language="F#" Value="member this.IdentityProvider : string" Usage="Microsoft.Identity.Client.IUser.IdentityProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Identitätsanbieter ab, wenn vom Dienst zurückgegeben. Wenn dies nicht der Fall ist, wird der Wert ist null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.IUser.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Identity.Client.IUser.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Vorname des Benutzers ab, wenn vom Dienst bereitgestellt. Wenn dies nicht der Fall ist, wird der Wert ist null.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>