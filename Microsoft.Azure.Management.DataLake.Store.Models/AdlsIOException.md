<Type Name="AdlsIOException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException">
  <TypeSignature Language="C#" Value="public class AdlsIOException : Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsIOException extends Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsIOException&#xA;Inherits AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsIOException = class&#xA;    inherit AdlsRemoteException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("IOException")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine WebHDFS-Ausnahme ausgelöst, der angibt, es ist ein e/a (Lesen oder Schreiben)-Fehler. Wird ausgelöst, wenn ein Antwortcode 403-Fehler (Unzulässige).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsIOException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AdlsIOException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsIOException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsIOException (javaClassName, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="javaClassName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="javaClassName">Das vollständige Paket Klassenname für die Ausnahme ausgelöst wird, z. B. "java.lang.IllegalArgumentException".</param>
        <param name="message">die die ausgelöste Ausnahme, z. B. zugeordnete Meldung ' Ungültiger Wert für Webhdfs-Parameter "Berechtigung":... ".</param>
        <summary>
            Initialisiert eine neue Instanz der AdlsIOException-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>