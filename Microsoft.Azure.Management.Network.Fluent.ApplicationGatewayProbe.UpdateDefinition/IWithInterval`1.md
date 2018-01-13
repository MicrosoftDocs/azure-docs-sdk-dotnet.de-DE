<Type Name="IWithInterval&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithInterval&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInterval`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInterval(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithInterval&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase einer Anwendung Gateway Prüfpunkt Definition Möglichkeit zum Angeben des Zeitintervalls zwischen aufeinander folgenden Prüfpunkte.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeBetweenProbesInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTimeBetweenProbesInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTimeBetweenProbesInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithInterval`1.WithTimeBetweenProbesInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeBetweenProbesInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeBetweenProbesInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithInterval.WithTimeBetweenProbesInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds">Eine Zahl zwischen 1 und 86400 Sekunden.</param>
        <summary>
            Gibt das Zeitintervall in Sekunden zwischen aufeinanderfolgenden Prüfpunkte an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>