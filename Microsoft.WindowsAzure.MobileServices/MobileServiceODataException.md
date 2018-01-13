<Type Name="MobileServiceODataException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException">
  <TypeSignature Language="C#" Value="public class MobileServiceODataException : InvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceODataException extends System.InvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceODataException&#xA;Inherits InvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServiceODataException = class&#xA;    inherit InvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.InvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Typ der Ausnahme, die Ausnahmen beim Analysieren der OData-Abfragen darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="message">Die Nur-Text-Fehlermeldung für diese Ausnahme.</param>
        <param name="errorPos">Die Position in der Zeichenfolge, in denen Fehler vorhanden ist.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" />-Klasse mit einer Fehlermeldung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceODataException (string message, int errorPos, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, int32 errorPos, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.#ctor(System.String,System.Int32,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, errorPos As Integer, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException : string * int * Exception -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceODataException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceODataException (message, errorPos, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorPos" Type="System.Int32" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Nur-Text-Fehlermeldung für diese Ausnahme.</param>
        <param name="errorPos">Die Position in der Zeichenfolge, in denen Fehler vorhanden ist.</param>
        <param name="innerException">Die interne Ausnahme, die diese ausgelöste Ausnahme verursacht hat.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.MobileService.MobileServiceODataException" />-Klasse mit einer Fehlermeldung und einer internen Ausnahme.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorPosition">
      <MemberSignature Language="C#" Value="public int ErrorPosition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorPosition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorPosition As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorPosition : int" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceODataException.ErrorPosition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Position in der Zeichenfolge, in dem Fehler ist vorhanden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>