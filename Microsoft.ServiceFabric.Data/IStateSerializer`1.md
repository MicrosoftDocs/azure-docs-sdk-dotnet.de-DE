<Type Name="IStateSerializer&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IStateSerializer&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IStateSerializer&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateSerializer`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IStateSerializer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateSerializer(Of T)" />
  <TypeSignature Language="F#" Value="type IStateSerializer&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">Geben Sie zum Serialisieren und deserialisieren.</typeparam>
    <summary>
             Stellt ein benutzerdefiniertes Serialisierungsprogramm für den Typ <typeparamref name="T" />.
             </summary>
    <remarks>
             Verwendung <see cref="M:Microsoft.ServiceFabric.Data.IReliableStateManager.TryAddStateSerializer``1(Microsoft.ServiceFabric.Data.IStateSerializer{``0})" /> zum Registrieren eines benutzerdefinierten Serialisierers.
             </remarks>
    <example>
             In diesem Beispiel Implementierung der Lese- und Schreibberechtigungen Überladungen rufen Sie einfach ihre Entsprechung Überladungen.
             Die CurrentValue und BaseValue-Parameter werden von der Plattform nicht festgelegt und sollte ignoriert werden.
             <code>
             class Order
             {
                 public byte Warehouse { get; set; }
                 public short District { get; set; }
                 public int Customer { get; set; }
                 public long OrderNumber { get; set; }
             }
            
             class OrderSerializer : IStateSerializer&lt;Order&gt;
             {
                 void Write(Order value, BinaryWriter writer)
                 {
                     writer.Write(value.Warehouse);
                     writer.Write(value.District);
                     writer.Write(value.Customer);
                     writer.Write(value.OrderNumber);
                 }
            
                 Order Read(BinaryReader reader)
                 {
                     Order value = new Order();
            
                     value.Warehouse = reader.ReadByte();
                     value.District = reader.ReadInt16();
                     value.Customer = reader.ReadInt32();
                     value.OrderNumber = reader.ReadInt64();
            
                     return value;
                 }
            
                 void Write(Order currentValue, Order newValue, BinaryWriter writer)
                 {
                     this.Write(newValue, writer);
                 }
            
                 Order Read(Order baseValue, BinaryReader reader)
                 {
                     return this.Read(reader);
                 }
             }
             </code></example>
  </Docs>
  <Members>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read binaryReader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="binaryReader">Die <see cref="T:System.IO.BinaryReader" /> aus zu deserialisieren.</param>
        <summary>
            Deserialisiert aus der angegebenen <see cref="T:System.IO.BinaryReader" /> auf <typeparamref name="T" />.
            </summary>
        <returns>Der deserialisierte Wert.</returns>
        <remarks>
            Beim Zugriff auf die <see cref="T:System.IO.BinaryReader" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.
            Lesen muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Read">
      <MemberSignature Language="C#" Value="public T Read (T baseValue, System.IO.BinaryReader binaryReader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Read(!T baseValue, class System.IO.BinaryReader binaryReader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Read(`0,System.IO.BinaryReader)" />
      <MemberSignature Language="F#" Value="abstract member Read : 'T * System.IO.BinaryReader -&gt; 'T" Usage="iStateSerializer.Read (baseValue, binaryReader)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="binaryReader" Type="System.IO.BinaryReader" />
      </Parameters>
      <Docs>
        <param name="baseValue">Preis für die Deserialisierung.</param>
        <param name="binaryReader">Die <see cref="T:System.IO.BinaryReader" /> aus zu deserialisieren.</param>
        <summary>
            Deserialisiert aus der angegebenen <see cref="T:System.IO.BinaryReader" /> auf <typeparamref name="T" />.
            </summary>
        <returns>Der deserialisierte Wert.</returns>
        <remarks>
            Beim Zugriff auf die <see cref="T:System.IO.BinaryReader" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.
            Lesen muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T value, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T value, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (value, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="value">Der zu serialisierende Wert.</param>
        <param name="binaryWriter">Die <see cref="T:System.IO.BinaryWriter" /> zu serialisieren.</param>
        <summary>
            Serialisiert einen Wert und schreibt ihn auf den angegebenen <see cref="T:System.IO.BinaryWriter" />.
            </summary>
        <remarks>
            Beim Zugriff auf die <see cref="T:System.IO.BinaryWriter" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.
            Schreiben von muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Write">
      <MemberSignature Language="C#" Value="public void Write (T baseValue, T targetValue, System.IO.BinaryWriter binaryWriter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Write(!T baseValue, !T targetValue, class System.IO.BinaryWriter binaryWriter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IStateSerializer`1.Write(`0,`0,System.IO.BinaryWriter)" />
      <MemberSignature Language="F#" Value="abstract member Write : 'T * 'T * System.IO.BinaryWriter -&gt; unit" Usage="iStateSerializer.Write (baseValue, targetValue, binaryWriter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="baseValue" Type="T" />
        <Parameter Name="targetValue" Type="T" />
        <Parameter Name="binaryWriter" Type="System.IO.BinaryWriter" />
      </Parameters>
      <Docs>
        <param name="baseValue">Preis für die Serialisierung.</param>
        <param name="targetValue">Der zu serialisierende Wert.</param>
        <param name="binaryWriter">Die <see cref="T:System.IO.BinaryWriter" /> zu serialisieren.</param>
        <summary>
            Serialisiert ein Objekt und schreibt es an der angegebenen <see cref="T:System.IO.BinaryWriter" />.
            </summary>
        <remarks>
            Beim Zugriff auf die <see cref="T:System.IO.BinaryWriter" /> basisdatenstrom, muss darauf geachtet werden, wenn die Position im Stream verschoben.
            Schreiben von muss auf die aktuelle Streamposition beginnen und enden an der aktuellen Position plus die Länge der Daten.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>