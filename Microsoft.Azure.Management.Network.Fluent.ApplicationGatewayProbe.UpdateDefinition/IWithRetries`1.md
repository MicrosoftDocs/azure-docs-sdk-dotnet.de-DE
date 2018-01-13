<Type Name="IWithRetries&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRetries&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRetries`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRetries(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRetries&lt;'ParentT&gt; = interface" />
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
            Phase ein Gateway Prüfpunkt Anwendungsdefinition festlegen, dass die Anzahl der Wiederholungsversuche vor dem Server angeben, wird als fehlerhaft betrachtet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRetriesBeforeUnhealthy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithRetriesBeforeUnhealthy (int retryCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithRetriesBeforeUnhealthy(int32 retryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithRetries`1.WithRetriesBeforeUnhealthy(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRetriesBeforeUnhealthy (retryCount As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRetriesBeforeUnhealthy : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRetries.WithRetriesBeforeUnhealthy retryCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="retryCount">Eine Zahl zwischen 1 und 20 ein.</param>
        <summary>
            Gibt die Anzahl der Wiederholungsversuche an, bevor der Server als fehlerhaft eingestuft wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>