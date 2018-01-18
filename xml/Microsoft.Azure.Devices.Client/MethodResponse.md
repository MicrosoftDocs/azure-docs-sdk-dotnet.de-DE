<Type Name="MethodResponse" FullName="Microsoft.Azure.Devices.Client.MethodResponse">
  <TypeSignature Language="C#" Value="public sealed class MethodResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MethodResponse extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.MethodResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MethodResponse" />
  <TypeSignature Language="F#" Value="type MethodResponse = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b1d91-101">Die Datenstruktur darstellen, die Geräte und-Methode, die zum Auslösen einer Aktivität auf dem Gerät verwendet wird</span><span class="sxs-lookup"><span data-stu-id="b1d91-101">The data structure represent the Device Twin Method that is used for triggering an activity on the device</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MethodResponse (int status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.MethodResponse.#ctor(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (status As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.MethodResponse : int -&gt; Microsoft.Azure.Devices.Client.MethodResponse" Usage="new Microsoft.Azure.Devices.Client.MethodResponse status" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="b1d91-102">eine ganze Zahl Code Contianing eine Methode aufrufen Status.</span><span class="sxs-lookup"><span data-stu-id="b1d91-102">an integer code contianing a method call status.</span></span></param>
        <summary>
            <span data-ttu-id="b1d91-103">Konstruktor befindlichen Eingabebytearrays als Text</span><span class="sxs-lookup"><span data-stu-id="b1d91-103">Constructor which uses the input byte array as the body</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MethodResponse (byte[] result, int status);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] result, int32 status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.MethodResponse.#ctor(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (result As Byte(), status As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Devices.Client.MethodResponse : byte[] * int -&gt; Microsoft.Azure.Devices.Client.MethodResponse" Usage="new Microsoft.Azure.Devices.Client.MethodResponse (result, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="result" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.InteropServices.WindowsRuntime.ReadOnlyArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
        <Parameter Name="status" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="result"><span data-ttu-id="b1d91-104">durch Aufruf der Methode zurückgegebenen Daten.</span><span class="sxs-lookup"><span data-stu-id="b1d91-104">data returned by the method call.</span></span></param>
        <param name="status"><span data-ttu-id="b1d91-105">Status, wodurch der Erfolg oder Fehler.</span><span class="sxs-lookup"><span data-stu-id="b1d91-105">status indicating success or failure.</span></span></param>
        <summary>
            <span data-ttu-id="b1d91-106">Stellen Sie eine neue Instanz der Klasse zurück, und überprüft, ob die Nutzlast korrekt JSON.</span><span class="sxs-lookup"><span data-stu-id="b1d91-106">Make a new instance of the return class and validates that the payload is correct JSON.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>