<Type Name="IWithTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTimeout&lt;'ParentT&gt; = interface" />
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
            Fehler bei der Phase von einer Anwendung Gateway Prüfpunkt Definition ermöglicht die Zeitspanne, nach dem Angeben der Prüfpunkts betrachtet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithTimeoutInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithTimeoutInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithTimeout`1.WithTimeoutInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeoutInSeconds (seconds As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTimeoutInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTimeout.WithTimeoutInSeconds seconds" />
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
            Gibt die Zeitdauer in Sekunden an, das Warten auf eine Antwort, damit der Test ist fehlgeschlagen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>