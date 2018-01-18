<Type Name="TooManyDevicesException" FullName="Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException">
  <TypeSignature Language="C#" Value="public sealed class TooManyDevicesException : Microsoft.Azure.Devices.Common.Exceptions.IotHubException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit TooManyDevicesException extends Microsoft.Azure.Devices.Common.Exceptions.IotHubException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TooManyDevicesException&#xA;Inherits IotHubException" />
  <TypeSignature Language="F#" Value="type TooManyDevicesException = class&#xA;    inherit IotHubException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Devices.Common.Exceptions.IotHubException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a1475-101">Ausnahme ausgelöst, wenn die Liste der Geräte Eingabe für einen Vorgang zu groß ist</span><span class="sxs-lookup"><span data-stu-id="a1475-101">Exception thrown when the list of input devices is too large for an operation</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TooManyDevicesException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException : string -&gt; Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException" Usage="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="a1475-102">Ctor nimmt eine Fehlermeldung</span><span class="sxs-lookup"><span data-stu-id="a1475-102">ctor which takes an error message</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TooManyDevicesException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException : string * Exception -&gt; Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException" Usage="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"></param>
        <param name="innerException"></param>
        <summary>
            <span data-ttu-id="a1475-103">Ctor nimmt eine Fehler-Nachricht mit eine innere Ausnahme</span><span class="sxs-lookup"><span data-stu-id="a1475-103">ctor which takes an error message alongwith an inner exception</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TooManyDevicesException (string message, string trackingId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, string trackingId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, trackingId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException : string * string -&gt; Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException" Usage="new Microsoft.Azure.Devices.Common.Exceptions.TooManyDevicesException (message, trackingId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="trackingId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"></param>
        <param name="trackingId"></param>
        <summary>
            <span data-ttu-id="a1475-104">Ctor nimmt eine Fehlermeldung und eine überwachungs-id</span><span class="sxs-lookup"><span data-stu-id="a1475-104">ctor which takes an error message and a tracking id</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>