<Type Name="CodePackageDebugParameters" FullName="System.Fabric.CodePackageDebugParameters">
  <TypeSignature Language="C#" Value="public class CodePackageDebugParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CodePackageDebugParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CodePackageDebugParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CodePackageDebugParameters" />
  <TypeSignature Language="F#" Value="type CodePackageDebugParameters = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Für Code Paketparameter-Debug-Klasse.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDebugParameters">
      <MemberSignature Language="C#" Value="public static string GetDebugParameters (System.Fabric.CodePackageDebugParameters[] debugParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetDebugParameters(class System.Fabric.CodePackageDebugParameters[] debugParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CodePackageDebugParameters.GetDebugParameters(System.Fabric.CodePackageDebugParameters[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetDebugParameters (debugParameters As CodePackageDebugParameters()) As String" />
      <MemberSignature Language="F#" Value="static member GetDebugParameters : System.Fabric.CodePackageDebugParameters[] -&gt; string" Usage="System.Fabric.CodePackageDebugParameters.GetDebugParameters debugParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="debugParameters" Type="System.Fabric.CodePackageDebugParameters[]" />
      </Parameters>
      <Docs>
        <param name="debugParameters">
          <para>Array von CodePackageDebugParameters, die in JSON serialisiert werden müssen. </para>
        </param>
        <summary>
          <para>
            JSON-Zeichenfolge zurück, die CodePackageDebugParameters darstellt übergeben.
            </para>
        </summary>
        <returns>
          <para>Entspricht der Zeichenfolgendarstellung der Debug-Parameter.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>