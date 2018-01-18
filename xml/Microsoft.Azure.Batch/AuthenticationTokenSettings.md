<Type Name="AuthenticationTokenSettings" FullName="Microsoft.Azure.Batch.AuthenticationTokenSettings">
  <TypeSignature Language="C#" Value="public class AuthenticationTokenSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthenticationTokenSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthenticationTokenSettings" />
  <TypeSignature Language="F#" Value="type AuthenticationTokenSettings = class&#xA;    interface ITransportObjectProvider&lt;AuthenticationTokenSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3a618-101">Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="3a618-101">The settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationTokenSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.AuthenticationTokenSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a618-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a618-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.AccessScope Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.AccessScope Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.AuthenticationTokenSettings.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As AccessScope" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Batch.Common.AccessScope with get, set" Usage="Microsoft.Azure.Batch.AuthenticationTokenSettings.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.AccessScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a618-103">Ruft ab oder legt die Batch-Ressourcen, zu denen das Token Zugriff gewährt.</span><span class="sxs-lookup"><span data-stu-id="3a618-103">Gets or sets the Batch resources to which the token grants access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="3a618-104">Das Authentifizierungstoken gewährt nur Zugriff auf eine begrenzte Anzahl von Batch-Dienstvorgänge.</span><span class="sxs-lookup"><span data-stu-id="3a618-104">The authentication token grants access only to a limited set of Batch service operations.</span></span> <span data-ttu-id="3a618-105">Derzeit die einzige unterstützte Wert für die Eigenschaft für den Zugriff wird <see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />, die gewährt Zugriff auf alle Vorgänge im Zusammenhang mit der der Auftrag, der den Task enthält.</span><span class="sxs-lookup"><span data-stu-id="3a618-105">Currently the only supported value for the Access property is <see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />, which grants access to all operations related to the job which contains the task.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>