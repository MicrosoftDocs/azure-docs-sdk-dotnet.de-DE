<Type Name="IWithFrontendPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort&lt;'ParentT&gt; = interface" />
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
            Die Stufe der Gateway Front-End-Listener Anwendungsdefinition an den Front-End-Port zum Zuordnen des Listeners mit dem zulassen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort`1.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">eine Portnummer an.</param>
        <summary>
            Ermöglicht die Überwachung für die Anzahl der angegebene Front-End-Port gelauscht.
            Wenn Sie ein Front-End-Port für diese Portnummer noch nicht vorhanden ist, wird ein neues mit einem automatisch generierten Namen erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithFrontendPort`1.WithFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (name As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithFrontendPort.WithFrontendPort name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des einen vorhandenen Front-End-Port.</param>
        <summary>
            Ermöglicht die Überwachung für den angegebenen vorhandenen Front-End-Port lauschen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>