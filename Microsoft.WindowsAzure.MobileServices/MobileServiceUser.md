<Type Name="MobileServiceUser" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceUser">
  <TypeSignature Language="C#" Value="public class MobileServiceUser" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceUser extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceUser" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceUser" />
  <TypeSignature Language="F#" Value="type MobileServiceUser = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein authentifizierter Mobile Services-Benutzer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceUser (string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceUser : string -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceUser" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceUser userId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId">
            Benutzer-Id eines erfolgreich authentifizierten Benutzers.
            </param>
        <summary>
            Initialisiert eine neue Instanz der MobileServiceUser-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceAuthenticationToken">
      <MemberSignature Language="C#" Value="public virtual string MobileServiceAuthenticationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MobileServiceAuthenticationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.MobileServiceAuthenticationToken" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property MobileServiceAuthenticationToken As String" />
      <MemberSignature Language="F#" Value="member this.MobileServiceAuthenticationToken : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceUser.MobileServiceAuthenticationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein Microsoft Azure Mobile Services-Authentifizierungstoken für den Benutzer anhand der <see cref="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />. Wenn nicht Null ist, wird das Authentifizierungstoken in alle Anforderungen für Microsoft Azure Mobile Service, sodass des Clients alle Aktionen, die Berechtigungsstufe authentifizierter Benutzer erfordern Microsoft Azure Mobile Service enthalten sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public virtual string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Benutzer-Id eines erfolgreich authentifizierten Benutzers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>