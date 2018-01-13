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
            Die Datenstruktur darstellen, die Geräte und-Methode, die zum Auslösen einer Aktivität auf dem Gerät verwendet wird
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
        <param name="status">eine ganze Zahl Code Contianing eine Methode aufrufen Status.</param>
        <summary>
            Konstruktor befindlichen Eingabebytearrays als Text
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
        <param name="result">durch Aufruf der Methode zurückgegebenen Daten.</param>
        <param name="status">Status, wodurch der Erfolg oder Fehler.</param>
        <summary>
            Stellen Sie eine neue Instanz der Klasse zurück, und überprüft, ob die Nutzlast korrekt JSON.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>