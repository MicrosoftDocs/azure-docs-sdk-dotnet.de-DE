<Type Name="MobileServicePreconditionFailedException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException">
  <TypeSignature Language="C#" Value="public class MobileServicePreconditionFailedException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePreconditionFailedException extends Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePreconditionFailedException&#xA;Inherits MobileServiceInvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServicePreconditionFailedException = class&#xA;    inherit MobileServiceInvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Details zur HTTP-Antwort mit Statuscode "Fehler bei Vorbedingung"
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePreconditionFailedException (Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, Newtonsoft.Json.Linq.JObject value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, class Newtonsoft.Json.Linq.JObject value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException.#ctor(Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As MobileServiceInvalidOperationException, value As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException (source, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
        <Parameter Name="value" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="source">
            Die innere Ausnahme.
            </param>
        <param name="value">
            Die aktuelle Instanz vom Server, dem für die Vorbedingung nicht erfüllt.
            </param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>