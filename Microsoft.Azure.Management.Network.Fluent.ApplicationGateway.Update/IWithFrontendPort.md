<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase von einer Anwendung Gateway Update ermöglicht Front-End-Ports ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">eine Portnummer an.</param>
        <summary>
            Erstellt einen Front-End-Port mit einem automatisch generierten Namen und die angegebene Portnummer an, sofern diese nicht bereits eine vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer, name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort (portNumber, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="portNumber">eine Portnummer an.</param>
        <param name="name">Der Name der Port zuweisen.</param>
        <summary>
            Erstellt einen Front-End-Port mit dem angegebenen Namen und die Portnummer an, sofern diese kein Port, der Abgleich dieser Namen und/oder Anzahl bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition oder Null, wenn Sie einen Abgleich der Name oder die Anzahl jedoch nicht zu beiden Port ist bereits vorhanden.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">Die Nummer des Ports des Front-End-Ports zu entfernen.</param>
        <summary>
            Entfernt den angegebenen Front-End-Port an.
            Beachten Sie, dass entfernen einen Front-End-Port andere Einstellungen verweist das Anwendungsgateway unterbrechen kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Front-End-Ports zu entfernen.</param>
        <summary>
            Entfernt den angegebenen Front-End-Port an.
            Beachten Sie, dass entfernen einen Front-End-Port andere Einstellungen verweist das Anwendungsgateway unterbrechen kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>