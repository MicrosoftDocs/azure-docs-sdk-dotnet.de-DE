<Type Name="ServiceException" FullName="Microsoft.ServiceFabric.Services.Communication.ServiceException">
  <TypeSignature Language="C#" Value="public class ServiceException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type ServiceException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet Informationen zu einer Ausnahme vom Dienst an. Diese Ausnahme wird ausgelöst, wenn die eigentliche Ausnahme vom Dienst zum Übertragen an den Client nicht serialisiert werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceException (string actualExceptionType, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actualExceptionType, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.ServiceException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (actualExceptionType As String, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.ServiceException : string * string -&gt; Microsoft.ServiceFabric.Services.Communication.ServiceException" Usage="new Microsoft.ServiceFabric.Services.Communication.ServiceException (actualExceptionType, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actualExceptionType" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actualExceptionType">die ActualExceptionType der ausgelösten Ausnahme</param>
        <param name="message">Die Fehlermeldung, die die Ursache dieser Ausnahme erklärt wird
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Services.Communication.ServiceException" /> Klasse mit einer entsprechenden Meldung.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActualExceptionType">
      <MemberSignature Language="C#" Value="public string ActualExceptionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActualExceptionType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.ServiceException.ActualExceptionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActualExceptionType As String" />
      <MemberSignature Language="F#" Value="member this.ActualExceptionType : string" Usage="Microsoft.ServiceFabric.Services.Communication.ServiceException.ActualExceptionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ActualExceptionType ist der Typ des tatsächlichen ausgelöste Ausnahme.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>