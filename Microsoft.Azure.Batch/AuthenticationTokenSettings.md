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
            Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.AuthenticationTokenSettings" />-Klasse.
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
            Ruft ab oder legt die Batch-Ressourcen, zu denen das Token Zugriff gewährt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Das Authentifizierungstoken gewährt nur Zugriff auf eine begrenzte Anzahl von Batch-Dienstvorgänge. Derzeit die einzige unterstützte Wert für die Eigenschaft für den Zugriff wird <see cref="F:Microsoft.Azure.Batch.Common.AccessScope.Job" />, die gewährt Zugriff auf alle Vorgänge im Zusammenhang mit der der Auftrag, der den Task enthält.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>