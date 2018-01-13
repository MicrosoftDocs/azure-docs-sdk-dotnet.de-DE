<Type Name="AdalClaimChallengeException" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException">
  <TypeSignature Language="C#" Value="public class AdalClaimChallengeException : Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdalClaimChallengeException extends Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdalClaimChallengeException&#xA;Inherits AdalServiceException" />
  <TypeSignature Language="F#" Value="type AdalClaimChallengeException = class&#xA;    inherit AdalServiceException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.IdentityModel.Clients.ActiveDirectory.AdalServiceException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ee6c5-101">Der Ausnahmetyp ausgelöst, wenn bei tokenabruf ein Ansprüche Challenge-Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="ee6c5-101">The exception type thrown when a claims challenge error occurs during token acquisition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdalClaimChallengeException (string errorCode, string message, Exception innerException, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string errorCode, string message, class System.Exception innerException, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException.#ctor(System.String,System.String,System.Exception,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As String, message As String, innerException As Exception, claims As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException : string * string * Exception * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException (errorCode, message, innerException, claims)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode">To be added.</param>
        <param name="message">To be added.</param>
        <param name="innerException">To be added.</param>
        <param name="claims">To be added.</param>
        <summary>
            <span data-ttu-id="ee6c5-102">Initialisiert eine neue Instanz der Exception-Klasse für die Behandlung von Ansprüchen.</span><span class="sxs-lookup"><span data-stu-id="ee6c5-102">Initializes a new instance of the exception class for handling claims.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public string Claims { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException.Claims" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Claims As String" />
      <MemberSignature Language="F#" Value="member this.Claims : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AdalClaimChallengeException.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ee6c5-103">Ansprüche Herausforderung vom STS zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ee6c5-103">Claims challenge returned from the STS.</span></span> <span data-ttu-id="ee6c5-104">Dieser Wert sollte an die API-Aufrufer übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="ee6c5-104">This value should be passed back to the API caller.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>