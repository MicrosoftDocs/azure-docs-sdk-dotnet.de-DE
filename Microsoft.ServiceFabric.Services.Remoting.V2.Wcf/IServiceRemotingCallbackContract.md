<Type Name="IServiceRemotingCallbackContract" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingCallbackContract" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingCallbackContract" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingCallbackContract" />
  <TypeSignature Language="F#" Value="type IServiceRemotingCallbackContract = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ServiceModel.ServiceContract(Namespace="urn:ServiceFabric.Communication")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
             Definiert die Schnittstelle, die für das Bereitstellen von Rückrufmechanismus den Wcf-Remoting-Listener an den Client implementiert werden muss.
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="SendOneWay">
      <MemberSignature Language="C#" Value="public void SendOneWay (ArraySegment&lt;byte&gt; messageHeaders, System.Collections.Generic.IEnumerable&lt;ArraySegment&lt;byte&gt;&gt; requestBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SendOneWay(valuetype System.ArraySegment`1&lt;unsigned int8&gt; messageHeaders, class System.Collections.Generic.IEnumerable`1&lt;valuetype System.ArraySegment`1&lt;unsigned int8&gt;&gt; requestBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.Wcf.IServiceRemotingCallbackContract.SendOneWay(System.ArraySegment{System.Byte},System.Collections.Generic.IEnumerable{System.ArraySegment{System.Byte}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub SendOneWay (messageHeaders As ArraySegment(Of Byte), requestBody As IEnumerable(Of ArraySegment(Of Byte)))" />
      <MemberSignature Language="F#" Value="abstract member SendOneWay : ArraySegment&lt;byte&gt; * seq&lt;ArraySegment&lt;byte&gt;&gt; -&gt; unit" Usage="iServiceRemotingCallbackContract.SendOneWay (messageHeaders, requestBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ServiceModel.OperationContract(IsOneWay=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="messageHeaders" Type="System.ArraySegment&lt;System.Byte&gt;" />
        <Parameter Name="requestBody" Type="System.Collections.Generic.IEnumerable&lt;System.ArraySegment&lt;System.Byte&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="messageHeaders">Nachrichtenheader enthält die Informationen benötigt, um die Anforderung deserialisiert und zu sendende Meldung an den Client.</param>
        <param name="requestBody"> Nachrichtentext enthält eine Anforderung in serialisierter Form.</param>
        <summary>
            Sendet eine unidirektionale Nachricht an den Client.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>